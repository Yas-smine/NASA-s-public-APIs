# 🚀 Data Gathering with NASA Public APIs

## 🎯 Objective
Practice accessing and consuming NASA's public APIs to retrieve space-related data, process it using Python and pandas, and export the results for sharing.

---

## 🧠 Workflow Summary

1. **🔑 Generate Your API Key**  
   Visit the [NASA API Portal](https://api.nasa.gov) and request your personal API key via the registration form.

2. **📦 Setup Your Environment**  
   - Import the `requests` library for HTTP requests.  
   - Use `dotenv` and `os` to securely store and access your API key from a `.env` file.

3. **🖼️ Astronomy Picture of the Day (APOD)**  
   - Read the APOD documentation.  
   - Send a GET request to the APOD endpoint using your API key.  
   - Parse the response and display the image in your notebook.

4. **☄️ Asteroids - NeoWs Endpoint**  
   - Select the NeoWs API from the portal.  
   - Retrieve asteroid data and load it into a pandas DataFrame.

5. **🧹 Data Preprocessing**  
   Clean and structure the DataFrame to include:
   - `Asteroid ID`  
   - `Asteroid Name`  
   - `Minimal Estimated Diameter (km)`  
   - `Absolute Magnitude`  
   - `Relative Velocity (km/s)`

6. **📤 Export to CSV**  
   Save the cleaned DataFrame to a `.csv` file for sharing with colleagues or use in future analysis.

---

This checkpomini project reinforces API consumption, data wrangling, and file export—essential skills for practical data science workflows.
