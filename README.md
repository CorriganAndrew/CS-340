# CS-340

## Grazioso Salvare Rescue-Dog Dashboard

This project features an interactive dashboard that lets rescue trainers filter and inspect potential canine candidates for Water, Mountain, and Disaster missions. 
It was built for Grazioso Salvare using Python, JupyterDash, Dash Leaflet, and MongoDB.

---

### Key Features:
- Live shelter data connection via PyMongo and MongoDB
- Interactive table + bar chart + map, all in sync
- CRUD module (`animal_shelter.py`) encapsulates secure DB access
- Rescue-type filters for mission-specific sorting
- Deployment tweaks (Dash Leaflet, port changes, Apporto auth fixes)

---

### Reflection

**Q1: Maintainable, Readable, Adaptable Code**  
I built a CRUD module to cleanly separate database logic, which made the dashboard easier to read and reuse. Using Dash callbacks allowed UI elements to stay in sync with the database. 
If used elsewhere, the module and layout could easily be extended to support new rescue types or visualizations.

**Q2: Computer Science Mindset**  
My CS approach involved breaking the problem into modules and using pattern recognition to drive the layout and interactions. Past experience with API design helped shape my callbacks and filter logic. 
I reused problem-solving strategies like top-down design and debug isolation to resolve Apporto-specific issues.

**Q3: What Do Computer Scientists Do?**  
Computer scientists build tools that help organizations make decisions with data. This dashboard lets Grazioso trainers instantly evaluate rescue candidates based on key mission criteria, improving response speed and accuracy.
