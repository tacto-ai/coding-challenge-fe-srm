# Tacto Frontend Challenge 

## :tada: Congratulations! :tada:

Hello fellow engineer, if you're reading this, then we think you could be a good fit to join our team here at
Tacto. This challenge is designed to test your skills and see how you approach real-life product challenges that we
encounter here every day.

## The Challenge

We want you to build a simple web application that allows users to search for suppliers, add new ones, and view their details.
This application will serve as a mini-SRM (Supplier Relationship Management) system focused on managing supplier information.

### Application Features

- **Search for Suppliers:** Users should be able to search for suppliers by name and supplier number. The search results
  should update in real-time as the user types their query.
- **Add New Suppliers:** There should be a form in a modal/drawer to add new suppliers. The form should collect the following information:
    - Supplier Name
    - Supplier Number
    - Addresses: A Supplier can have multiple addresses. Each address should have the following fields:
        - Site Name (e.g. Head Office, Warehouse, etc.)
        - Address Line 1
        - Address Line 2
        - City
        - State
        - Zip Code
        - Country
    - Phone Number
    - Website
- **View Supplier Details:** Users should be able to click on a supplier from the search results to view more detailed information about them.
  - Include a map showing the location of the supplier's addresses. 
- **Responsive Design:** The application should be responsive and work well on both desktop and mobile devices like tablets.

### Technical Requirements
- **Frontend Framework:** The application should be built using React and Typescript.
- **State Management:** Use appropriate state management techniques to manage the application state.
- **Styling:** Feel free to use any CSS framework or library you are comfortable with, or just plain CSS/SASS, but make it beautiful.
- **API Mocking:** Since this is a frontend challenge, you do not need to create a backend. Instead, mock the API responses. You can use tools like MirageJS, MSW (Mock Service Worker), or simply hard-code some initial data.
- **Testing:** Write tests for parts of the application you think should be tested.


### Bonus Points
- Address Autocomplete: Use a third-party service like Google Places API to provide address autocomplete functionality in the address fields.
- Address Geocoding: Use a third-party service like Google Maps API to geocode the addresses and display them on a map.

### Evaluation Criteria
- **Functionality:** Does the application work as described in the features?
- **Code Quality:** Is the code clean, well-organized, and properly commented?
- **UI/UX Design:** Is the application easy to use and visually appealing?
- **Creativity and Initiative:** Bonus features or thoughtful touches that enhance the user experience.
- **Git Usage:** Are you committing often? Are your commit messages clear and descriptive?

### Submission
- Create a descriptive PR with your solution and describe your approach and any trade-offs you made.
- This is a rather open-ended challenge, so make your assumptions clear in the PR description.


