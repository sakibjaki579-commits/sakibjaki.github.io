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

| UC2 | View pharmacy details|
| -------------------------------------- | ------------------- |
| **Description** | A patient wants to view detailed for pharmacies about a selected pharmacy, such as its address, distance, ratings and reviews. This is here because it hepls users decide whether it meets their need.|
| **Actors** | Patient |
| **Assumptions** | The patient can access the app. The pharmacy data is available from the Open Data dataset. The patient has already searched for nearby pharmacies. |
| **Steps** | The patient opens the 'Find a pharmacy' feature and enters their location. The system then searches for pharmacies nearby and displays a list. The system displays detailed information about the selected pharmacy, including address, distance ratings and reviews.|
| **Variations** | If detailed information is unavailable, the system will display a message showing limited data. The patient can return to the results list at any time.|
| **Non-functional** | Pharmacy details should load quickly. Information should be clearly laid out and easy to read for all types of users.|
| **Issues** | keeping pharmacy information updated; Handling missing or incomplete data from the dataset|

| UC3 | Filter pharmacies by location/criteria|
| -------------------------------------- | ------------------- |
| **Description** | A patient wants to filter the list of nearby pharmacies based on specific criteria such as distance or location in order to narrow down the results and find the most suitable pharmacy much more efficiently.|
| **Actors** | Patient |
| **Assumptions** | The patient can access the app. A list of nearby pharmacies has already been displayed. Pharmacy data supports filtering by location or distance. |
| **Steps** | The patient searches for nearby pharmacies. The systm will display a lkist of available pharmacies. The patient selects one or more filter options. The system then searches for pharmacies nearby and displays a list and updates it depending on the criteria.|
| **Variations** | If no pharmacies match the selected filters, the system displays a message suggesting the user broaden the search criteria. The patient can reset the filters to view all results again.|
| **Non-functional** | Filtering should be applied instantly without any delays. The interface should clearly show which filters are currently active.|
| **Issues** | Ensuring that filter options match the actual data available from the dataset. Being able to handle situations where filtered results are very limited or empty.|

| UC4 | Save pharmacy to favourites|
| -------------------------------------- | ------------------- |
| **Description** | A patient wants to save a pharmacy to their personal favourites list so they can quickly access it later. This allows patients to keep track of trusted or frequently used pharmacies.|
| **Actors** | Patient |
| **Assumptions** | The patient is logged into the app.The pharmacy exists in the system’s database. |
| **Steps** | The patient views the list of nearby pharmacies.The patient selects the “Save to favourites” option next to a pharmacy.The system saves the pharmacy to the patient’s favourites list.The system shows a confirmation message.The patient can later view their list of favourite pharmacies.|
| **Variations** | If a pharmacy is already saved, the system shows “Already in favourites”.|
| **Non-functional** | Response for saving/removing a favourite should be fast and feel instantaneous.|
| **Issues** |Keeping favourites synced across devices.|


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/32055927-c07b-4667-b4b1-d57b32cb1e84" />





## Software Requirements Specification
### Functional requirements
1. **FR1** | The system shall request permission to access the patient's current location. - UC1 |
2. **FR2** | The system shall allow the patient to manually enter their location if GPS is denied. - UC1 |
3. **FR3** | The system shall search for pharmacies within the patient's area using the provided location. - UC1 |
4. **FR4** | The system shall display each pharmacies name, distance, rating and reviews. - UC1 |
5. **FR5** | The system shall allow the patient to save/remove a selected pharmacy to their favourites list. - UC4 |
6. **FR6** | The system shall prevent duplicate entries by checking if the pharmacy is already saved. - UC4 |
7. **FR7** | The system shall confirm to the patient that the pharmacy has been successfully saved.	- UC4 |
8. **FR8** | The system shall allow the patient to view a list of their saved favourite pharmacies. - UC4 |

### Non-Functional Requirements
Indicate which UC the requirement comes from.

1. **Efficiency**   | NFR1. The system shall load pharmacy search result quickly. - UC1 |
2. **Usability**    | NFR2. The system shall provide a simple and easy to read interface for every user. - UC1 |
3. **Reliability**  | NFR3. The system shall ensure the pharmacy data are up to date. - UC1 |
4. **Functionality**| NFR4. The system shall be able to handle large number of users without malfunctioning. - UC1 |
5. **Performance**  | NFR5. The system shall save a pharmacy to the favourites list within 2 seconds. - UC4 |
6. **Usability**    | NFR6. The system shall present the “Save to favourites” option clearly so that users can understand it without instruction.  - UC4 |
7. **Reliability**  | NFR7. The system shall ensure the favourites list remains consistent even if the app is closed or restarted. - UC4 |
8. **Security**     | NFR8. The system shall store the favourites list securely and associate it only with the patient’s authenticated account. - UC4 |
