# LinkedIn Data Mart

## Purpose
- **Streamline LinkedIn profile data management.**
- **Create a structured SQL database** from JSON data extracted via API.
- **Visualize processed data using Tableau** for effective exploration and analysis.

---

## Architecture

### Three Main Stages

1. **ETL Pipeline:**
   - **Extraction:** Retrieve LinkedIn profile data and images in JSON format via API.
   - **Transformation:** Normalize data through over 10 transformations to convert JSON into structured SQL tables.
   - **Loading:** Store processed data into an SQL database.

2. **Data Mart:**
   - Utilize the SQL database for LinkedIn profile information storage.

3. **Visualization:**
   - Import the SQL database into Tableau to create multiple visualizations, culminating in a comprehensive interactive dashboard.
   - **Key Features:**
     - **Interactive Search Filter:** Search profiles by job title, skills, education, etc.
     - **Drill-Down Capabilities:** Clickable elements for detailed information.
     - **Dynamic Updates:** Real-time updates based on filter criteria.

---

## Technologies Used
- **Pentaho ETL:** For data extraction, transformation, and loading processes.
- **SQL:** For data storage and normalization.
- **Tableau:** For data visualization and dash
