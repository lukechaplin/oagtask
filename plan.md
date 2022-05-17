#Backend Plan

- Use express generator package to create backend microservice structure for server
- Create restful API HTML routes for server that will query specific API endpoints
- These routes will include functions with specific fetch requests that will connect to the API endpoints and return relevant data
- Allow it so that certain parameters in html routes can be passed to the fetch requests so that the data linked to those parameters is returned
- To save data have option to link to some form of database on the backend e.g. SQL/Firebase and searched data is posted there for retrieval later: would require some form of authentication
- Would have a HTML route with a post request that would have data passed from the front end that would be triggered by user on the front end using a onClick event linked to a button.

#Frontend Plan

- Use create react app to generate basic folder structure for a react front end
- Use react router dom package to allow for different pages linked to different server HTML routes
- Write component that can be used for each page that will include input field
- Write component that will include onchange function that can be used by input field and exported to each page
- Write components for each html route that can be exported to the relevant pages that will include the option to pass the input as a parameter to the html route so this can be passed to the backend to be handled appropriately, these components will be wrapped in a useEffect
- Write functions in the above component that will be the condition the useEffects use to run contained component - in this case an onClick event

#What I would add as additional features if I had more time/what would I do differently

- Create high fidelity wireframes
- Add a dark mode
- Go through plan to assess that accesbility was throughly considred: colours work for people with colour blindess/sigh difficulties, appropriate HTML tags for screen readers etc
- Think about responsiveness and how the app would look on different screeen sizes/devices
- Consider need for different language options
- Consider authentication/log in for easier search/booking retrival for users
- If I was to do this differently - fetch requests could be written on the front end and linked to input fields that way (input being passed into part of fetch URL as needed) and then button click to send request and return the data.
- This would be a quicker way of reaching MVP

#Why do I want to work at OAG

Being able to work for a top 50 UK tech company that can trace its route back to 1929 would be amazing - as your company has the history and expertise that comes with being involved in aviation from the very begining.
The chance to work with data that enables airlines, airports and travel technology companies to design innovative products, responsive services and seamless experiences would be incredible and would provide me with an amazing learning and trianing experience as a junior developer.
