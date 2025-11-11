# Ghost_Bus_Detector-GTFS-
Real Time Ghost Bus Tracker, a system that keeps track of live bus activity and flags "Ghost Buses,” which are buses shown in schedules but missing in real life. It’s built with FastAPI, Redis, and React, processes live "GTFS data", and shows everything on an interactive map with real-time alerts and analytics.

##  Use Case
The system is designed for daily commuters and tourist who depend on public transportation.  
By identifying and filtering out unreliable or inactive bus data, it helps reduce uncertainty and wait times, empowering users to make better travel decisions based on the actual operational status of buses.

---

##  Key Modules
- Real-Time Transit Data Ingestion Service (GTFS-Realtime) – Fetch and parse live transit data.
- Geospatial Anomaly Detection Engine – Identify off-route or inactive buses.
- Ghost Bus Flagging Logic – Mark buses that are non-operational or delayed.
- Live Transit Map Dashboard (WebSockets) – Visualize active buses and ghost buses on an interactive map.
- Clean Transit Data API – Serve validated, real-time bus data to client applications.

---

##  Tools & Technologies

| Category | Tools / Frameworks |
|---------------|------------------------|
| Backend & Analytics | Python, FastAPI, WebSockets, GeoPandas |
| Database | Redis (for real-time caching) |
| Frontend | React.js, Leaflet or Mapbox |
| DevOps & General | Docker, Git |

---

##  Final Deliverables
-  A real-time data pipeline that cleans and validates public transit data.  
-  An analytics engine that detects and flags Ghost Bus anomalies.  
-  An interactive map dashboard that visualizes the live, operational fleet.  
-  A complete repository with code, documentation, and demo setup.

---

##  Suggested Repository Names
- ghost-bus-tracker (clean and descriptive) 
- phantom bus-detector (unique and creative)  
- Realtime-transit-analyzer (technical and professional)
- smart-transit-monitor (enterprise-style naming)

---

##  Future Enhancements
- Integrate predictive analytics to estimate delays based on route and time.  
- Add user-side mobile notifications for ghost bus alerts.  
- Include multi-city support with dynamic configuration.  

---

## Author
   Manoj Chigateri -  
   Data Analyst & Developer passionate about real-time analytics, geospatial insights, and impactful data solutions.

---

  If you like this project, don’t forget to star the repository!
