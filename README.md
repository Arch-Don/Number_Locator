# Phone Number Geolocation Mapper
## CODE: [python_script](/number_location_finder.ipynb)
# Overview
![map](/images/map.png)

**A Python project that extracts geographic information from a phone number, converts the location into geographic coordinates using the OpenCage Geocoding API, and visualizes the result on an interactive map using Folium.**

## 🔼Features
- **Parse international phone numbers.**  
- **Identify the geographic region associated with a phone number.**  
- **Detect the carrier/network provider.**  
- **Convert location names into latitude and longitude coordinates.**  
- **Generate an interactive HTML map with a location marker.**
- **Save the map for offline viewing.**
## 💡Technologies Used
- Python 3
- phonenumbers
- OpenCage Geocoding API
- Folium
## ⚙Installation
### Install Dependencies
- pip install phonenumbers opencage folium
- Getting an OpenCage API Key
- Create an account at OpenCage.
- Generate an API key from your dashboard.
- Replace the API key in the script:
    - key = "YOUR_API_KEY"  

## 📤Example Output
 Location: Nigeria  
Carrier: MTN

![output](/images/sample.png)

### The script generates:

- mymap.html

- Open the generated file in a web browser to view the interactive map.


## Limitations
- The location returned by phonenumbers is based on phone number metadata and numbering plans.  
- The map does not show the real-time or precise location of the phone owner.  
- Mobile number portability may affect carrier accuracy.  
- Results depend on the quality of the geocoding data returned by OpenCage.  


