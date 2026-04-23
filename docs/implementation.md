# Implementation

## Introduction
The system implemented is a web-based Pharmacy Finder application that allows users to search for nearby pharmacies using their postcode. The website provides a simple interface where users enter a postcode and the system returns pharmacies within a specified distance radius.

The system is designed to help users quickly locate pharmacies in their local area. The search feature is optimized for speed and convenience, allowing users to find pharmacies within a 2-mile radius of their entered postcode.

## Project Structure
The Pharmacy Finder website is organised into folders and files that separate different parts of the system such as the user interface, styling, and functionality. This structure makes the system easier to maintain, update, and debug.

Files:

index.html = Main home page of the website to search for pharmacies

Favourite.html = Favourite page for adding favourite pharmacies

style.css = Controls the layout, font and colour of the website

script.js = Handles search functionality and user interactions

<img width="1391" height="676" alt="image" src="https://github.com/user-attachments/assets/0f169edf-9f36-4a67-93ad-3627897e59b2" />


## Software Architecture
The Pharmacy Finder system is built using a web-based architecture consisting of several major components that work together to deliver the service to users. Each component has a specific role in processing user input, retrieving pharmacy data, and displaying results.

<img width="800" height="533" alt="image" src="https://github.com/user-attachments/assets/2182dbc9-6238-4371-9418-c7079766206d" />


## Bristol Open Data API
TODO: Document each query to Bristol Open Data

![UML Class diagrams representing JSON query results](images/class1.png)
TODO: Repeat as necessary

# User guide
UC1 - Entering a valid postcode and filtering it by nearest
<img width="1887" height="992" alt="image" src="https://github.com/user-attachments/assets/9a27ae79-91a5-4574-a478-5dd9467c2cdb" />

UC2 - Viweing pharmacy details via Google maps and making sure that reviews and ratings are displayed along within 2 mile radius. Doesn't notify if unavalable.
<img width="1868" height="1003" alt="image" src="https://github.com/user-attachments/assets/8ec50455-0ed7-45d1-bb5e-b8de4014cf41" />

UC3 - Filtering works but becasue the postcode is in a 2 mile radius filtering wasn't needed for distance.
<img width="1872" height="992" alt="image" src="https://github.com/user-attachments/assets/4b6fa273-f87b-450b-99e3-e36536e070b1" />

UC4 - Favourites work when even reloading the page and it is saved.
<img width="1907" height="777" alt="image" src="https://github.com/user-attachments/assets/e1ec84cf-dc3d-43aa-9990-92e90b7bd025" />




