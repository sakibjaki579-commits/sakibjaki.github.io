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

![Insert your Use-Case Diagram Here](images/use-case.png)

## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.


### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.
