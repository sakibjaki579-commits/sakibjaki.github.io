# Testing

## Test Plan

Test Case ID	| Test Description	| Steps	| Expected Results |	Actual Result	| Pass/Fail
TC1	Search using Valid Postcode	Enter Valid Postcode and click search	List pharmacy nearby 2 miles 	Does as expected	Pass
TC2 	Clicking search button with nothing in box	Don’t enter anything 	Should display a message saying to enter a postcode	Does as expected	Pass
TC3 	Adding favourites should display on the favourites page	Click on ‘add to favourites’	Adds the pharmacy to the favourites page	Does as expected	Pass
TC4	Show miles within 2 miles	Search using valid postcode	Should display miles 	Does as expected	Pass
TC5	Map displays on Google	Click on ‘view on Google maps’	Should take you to Google maps	Does as expected	Pass
TC6	Shows reviews with stars	Search using valid Postcode	Should display reviews with stars	Does as expected	Pass
TC7	Shows on phone	Use phone to access website	Should display website on phone perfectly	Does as expected	Pass
TC8	Clear all favourites	Click clear all favourites	Should wipe away all your favourites	Does as expected	Pass
TC9	Switch to favourites page	Click on favourites page	Should take you to favourites page	Does as expected 	Pass
TC10	Display error	Enter invalid postcode	Adding in invalid postcode should display error	Doesn’t work	Fail
TC11	Fast display	Add a valid postcode	Should search pharmacies quickly	Does as expected	Pass






