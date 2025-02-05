## Whodunnit: The Keiko Corp Data Breach Case
This project tackles the case of Keiko Corp's 2024 data breach by tracing the movements of an insider who used the company’s free ride-sharing service to access confidential data. By analyzing employee records and location data, we solved the mystery of how an insider exploited the company’s resources to breach the data system.

---

### **Clues Given:**
- **Date of Breach:** The breach happened on **June 23, 2024**.
- **Location Range:** The culprit must have been physically present within the company's location on that day, which is identified by the following latitude and longitude ranges:  
  **Longitude:** -74.997 to -74.9968  
  **Latitude:** 40.5 to 40.6
- **Employee Insider:** The culprit is an employee who used the free ride-sharing service (Movr) available to employees and their families.

---

### **Steps Taken:**
1. **Filtered the Rides:** We filtered the ride data by the date of the breach (June 23, 2024).
2. **Location Analysis:** We narrowed down the location data by focusing on vehicles that were within the specific latitude and longitude range on that day.
3. **Identified Rider Names:** Extracted the rider names from the data that matched the location and time criteria.
4. **Employee Matching:** Cross-referenced the rider names with the employee database to identify any shared last names between the riders and employees.
5. **Culprit Identified:** Based on the name match, we successfully identified the employee (Parke Morris), who was responsible for the breach.
