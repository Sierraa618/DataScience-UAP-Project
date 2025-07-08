# Investigating the Correlation Between UAP Sightings and U.S. Military or Nuclear Sites

This project was developed as part of our Undergraduate Academic Project (UAP) at California State University San Marcos. Our team set out to determine whether Unidentified Aerial Phenomena (UAP) sightings are more likely to occur near U.S. military bases or nuclear sites. 

We combined verified government datasets with web-scraped public reports, conducted spatial and statistical analysis using SQL, and visualized our findings in Excel. The project also included a basic linear regression model to measure the strength of correlation between sightings and proximity to high-security facilities.

---

## 📍 Project Objective

To investigate whether UAP sightings reported on official and accredited government platforms show a stronger spatial correlation when located near U.S. military installations or nuclear power plants.

---

## 🔎 Methodology

### 1. **Data Collection**
We sourced and verified data from:
- U.S. government-maintained UAP/UFO public reporting databases
- Web scraping from reputable UAP reporting platforms using Python (BeautifulSoup)
- Official coordinates for U.S. military bases and nuclear facilities from public datasets

### 2. **Data Preparation**
- Cleaned and standardized records with Python and Pandas
- Converted all geographic references into latitude and longitude coordinates
- Cross-referenced sightings with verified facility locations

### 3. **SQL Analysis**
Imported all structured data into a SQL database to:
- Identify and count UAP sightings within 20-mile radii of military or nuclear sites
- Categorize sightings by proximity to different military branches
- Filter results by region, time, and sighting characteristics

### 4. **Linear Regression Modeling**
- Built a basic linear regression model to examine the relationship between the number of sightings and their distance to military or nuclear locations
- Dependent variable: Number of sightings per location
- Independent variable: Distance from nearest facility
- Results suggested a **moderate inverse correlation**, indicating that sightings were more frequent near military or nuclear zones

### 5. **Excel Visualizations**
Final datasets were used to create a series of Excel dashboards:
- Heat maps showing sighting densities near key regions
- Pivot charts comparing frequency by branch and region
- Line graphs visualizing sighting trends over time

---

## 📁 Project Structure (Archived Workflow)

While the original working files are no longer available, the structure below outlines how the project was organized:


/data
uap_sightings_cleaned.csv # Cleaned UAP report data
military_base_locations.csv # Verified coordinates of U.S. military bases
nuclear_site_coordinates.csv # Locations of U.S. nuclear facilities

/sql
correlation_queries.sql # SQL queries for proximity analysis
schema_structure.png # Diagram of the database schema

/visuals
proximity_heatmap.xlsx # Heatmap of sightings near facilities
sightings_by_branch.xlsx # Charts breaking down sightings by branch

/reports
final_uap_analysis.pdf # Final research report
presentation_slides.pdf # Visual slide deck
methodology.md # Step-by-step methodology and tools used



---

## 🧠 Key Findings

- Over **72,000 sightings** occurred within 20 miles of a U.S. military base
- Navy and Air Force bases accounted for the highest nearby sighting activity
- Linear regression suggested a measurable relationship between sighting frequency and proximity to secured infrastructure
- Geographical clusters showed meaningful overlap with facility locations, supporting the hypothesis of spatial correlation

---

## 💡 Skills Demonstrated

- Web scraping and data cleaning with Python
- SQL for geospatial querying and relational joins
- Data modeling with linear regression
- Visualization using Excel (pivot charts, heat maps, timelines)
- Team collaboration and academic presentation

---

## 👨‍🎓 Project Team

- **Sierra Norris**  
- Anthony Finn  
- Max Dunwoodie  
- Jessica Escobedo  
- Keeyana Newman  
- Jesus Mentado  
- Zach Solomons  

California State University San Marcos  
B.S. in Computer Information Systems — Spring 2025  
Undergraduate Academic Project (UAP)

---

## ✅ Project Status

**Completed**  
All research and presentation materials submitted for academic credit. The final presentation showing the completed showing of our findings is linked below. 


[Try Magic Design.pdf](https://github.com/user-attachments/files/21112088/Try.Magic.Design.pdf)




