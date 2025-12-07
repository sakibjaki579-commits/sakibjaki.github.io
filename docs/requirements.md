# Requirements

## User Needs

### User stories
As a patient, I want to search for pharmacies near my location and also see their ratings and reviews, so I can quickly find one that meets my needs.

### Actors
1. Patient 
2. Healthcare provider 
3. Admin 


### Use Cases

| UC1 | Find nearby pharmacies| 
| -------------------------------------- | ------------------- |
| **Description** | A patient wants to search for pharmacies close to where they are and see ratings and reviews for each one. This helps the patient choose a pharmacy that is both convenient and trustworthy.|
| **Actors** | Patient |
| **Assumptions** | The patient can access the app. The system has up-to-date pharmacy information. The patient can enter their location |
| **Steps** | The patient opens the 'Find a pharmacy' feature and enters their location. The system then searches for pharmacies nearby and displays a list. The patient scrolls through the results, comparing pharmacies based on distance, ratings and reviews before selecting one to view more details.|
| **Variations** | If the patient denies location access, the system asks them to type in their location; If no pharmacies are found, the system shows a friendly message and suggests searching a wider area.|
| **Non-functional** | Search results should load quickly; The interface should be easy for all users to navigate.|
| **Issues** | keeping pharmacy information updated; Ensuring reviews are moderate and trustworthy.|


TODO: Your Use-Case diagram should include all use-cases.

<img width="2048" height="1109" alt="image" src="https://github.com/user-attachments/assets/652d9d5a-ef84-4643-ae1e-9d5babc065c5" />




## Software Requirements Specification
### Functional requirements
|**FR1** The system shall request permission to access the patient's current location. - UC1 |
|**FR2** The system shall allow the patient to manually enter their location if GPS is denied. - UC1 |
|**FR3** The system shall search for pharmacies within the patient's area using the provided location. - UC1 |
|**FR4** The system shall display each pharmacies name, distance, rating and reviews. - UC1 |


### Non-Functional Requirements
Indicate which UC the requirement comes from.

|**Efficiency**| NFR1. The system shall load pharmacy search result quickly. - UC1 |
|**Usability**| NFR2. The system shall provide a simple and easy to read interface for every user. - UC1 |
|**Reliability**| NFR3. The system shall ensure the pharmacy data are up to date. - UC1 |
|**Functionality**| NFR4. The system shall be able to handle large number of users without malfunctioning. - UC1 |
