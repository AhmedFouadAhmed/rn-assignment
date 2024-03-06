# React Native Interview Homework
The goal of the developer exercise is to take a quick dive into a React Native project and build a two screen contact manager app. and we will be evaluating the code.

## Timelines and Contact
Expected time of completion is around 1-2 days of development, fitting the minimum requirements.
## Setup and Running
You can write your entire app as you would with any React Native

### Turning In
Once you are satisfied in your progress, please push to a repo, and invite jaltarjami@ub.edu.sa melsaid@ub.edu.sa a.fouad@ub.edu.sa to it.

-------------------

## Project Setting
Here is our fake setting for the exercise:

We are building a new application around managing contacts in a user’s phone. The goal of the assignment is to get a contact list display and drill-in page for a selected contact. This will be the base of further development, so the code must be ready for additions and changes. At this time, we do not need the favorite contact to persist after app is closed.

### Data
Please read the contacts from the User's phonebook, and retrieve phone numbers, emails, and URLs for each contact.
### Screens

#### Contacts list
This screen should minimally show a scrollable sorted list of up to 500 contacts (alphabetically by first name) and a single favorited contact (displayed above the list and in the normal sort-order). Users should be able to scroll through the list of contacts and tap any contact to view their full contact info page.

#### Contact Details
The detailed contact information page should show the information of the chosen contact: emails, phone numbers, and anything else given in the contact data. The only interaction a user needs to perform at this time is to favorite the contact (There can only be one favorite - please make sure the interactions for overwriting current favorite are there). There should be a button to return to the contacts list.

### Extra Credit
#### Contacts list
- Contacts are searchable (type in name or number and see list filter)
- Contacts are in header-sorted list - like native iOS

#### Detailed Contact Info
- Favorite Contact select persists on app re-launch
- Ability to interact with contact data - call, email, visit website, open maps with any addresses
- Have fallbacks for contacts with missing details (first/last name, emails, phone numbers) or contacts that are deemed a company
- Images/Thumbnails for the contact with a placeholder for contacts without any
