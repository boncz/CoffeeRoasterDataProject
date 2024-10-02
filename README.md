# Coffee Availability By Roaster - Web Scraping Project

## Project Overview
This project is designed to scrape information about coffees for sale from select craft roasters and micro-roasters across the U.S. The goal is to create a comprehensive dataset that can be searched and filtered based on criteria such as country of origin, processing type, and flavor profile. This dataset will be used to develop a mobile application that helps coffee lovers find and explore unique coffee options from independent roasters.

### Main Features:
- **Web Scraping with BeautifulSoup**: Extract coffee details, including roaster name, coffee name, country of origin, tasting notes, processing method, and more.
- **Dynamic Pricing Extraction (In Progress)**: Working on scraping coffee sizes and prices from websites that use dynamic elements such as flexbox.
- **Data Storage in Pandas**: Coffee data is stored in a pandas DataFrame for further processing, analysis, and filtering.
- **Future Integration with Mobile App**: The scraped data will power a mobile app where users can search for coffee based on different criteria, view roaster locations on a map, and be redirected to purchase from roasters directly.

---

## Current Status
- Successfully scraped data from [Onyx Coffee Labs](https://onyxcoffeelab.com), including coffee names, descriptions, origins, and tasting notes.
- Started experimenting with extracting prices based on coffee size options (in progress).
- The project is set to expand by scraping additional roasters (e.g., Equator Coffees, Ruby Coffee Roasters).
- Basic data cleaning and formatting done using pandas to organize the data into a structured format.

---

## Future Plans
1. **Expand Web Scraping**:
   - Add data from 5–10 more craft roasters, ensuring consistency in data fields.
   - Improve scraping for dynamic price and size data using Selenium.

2. **Mobile App Development**:
   - Develop a cross-platform mobile app using **React Native**.
   - Implement search and filter functionality for users to easily find coffee by origin, processing method, and flavor profile.
   - Add a **"Buy Now"** button to redirect users to the roaster's website.

3. **Map Integration**:
   - Use the **Google Maps API** or **Mapbox** to display roaster locations on a map, helping users find local roasters or shops nearby.

4. **User Interaction**:
   - Implement user accounts where people can save their favorite coffees and roasters.
   - Add functionality for users to suggest new roasters, with an admin review process to verify data before scraping.

5. **Automation**:
   - Set up automated tasks to re-scrape data periodically, keeping the dataset up to date with the latest coffee offerings.

---

## Technologies Used
- **Python**: The core programming language used for web scraping and data processing.
- **BeautifulSoup**: For scraping static HTML content from websites.
- **Selenium** (In Progress): For handling dynamic content and websites that rely on JavaScript.
- **Pandas**: For organizing and analyzing the scraped data.
- **React Native** (Planned): To develop the mobile application.
- **Google Maps API / Mapbox** (Planned): To display roaster locations.

---


## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request with suggestions for additional features, improvements to the scraping process, or adding more roasters.



---

## Contact
If you have any questions, suggestions, or just want to chat about the project, feel free to reach out!

---

