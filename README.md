## Flask Application Design for A helper which goes through rental property listings, find the suitable ones and apply on user behalf

### HTML Files
1. **index.html**: This is the main HTML file that the user will see when they visit the application. It should include a form that allows the user to input their criteria for finding rental properties.
2. **results.html**: This HTML file will display the results of the user's search. It should include a list of all the rental properties that match the user's criteria.
3. **application.html**: This HTML file will allow the user to apply for a rental property. It should include a form that allows the user to enter their personal information and submit an application.

### Routes
1. **index**: This route will render the index.html file.
2. **results**: This route will handle the form submission from the index.html file. It will use the user's input to search for rental properties that match their criteria. The results will be displayed in the results.html file.
3. **application**: This route will render the application.html file.
4. **submit_application**: This route will handle the form submission from the application.html file. It will send the user's application to the landlord.