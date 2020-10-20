# Restaurant-Inspection-Report-App

The Restaurant-Inspection-Report Application displays restaurant inspection rating in surrey on a map and list.

## How it works
## Data Updates
Obtains data from two Surrey database url links :

http://data.surrey.ca/api/3/action/package_show?id=restaurants

http://data.surrey.ca/api/3/action/package_show?id=fraser-health-restaurant-inspection-reports

On runtime, if the application hasn't been updated for over 24 hours, the app will check for updates from the Surrey database.
Allows user to accept or decline update. 

The application will store previous database updates on user phone so that the program may be run offline. 

## The Map
Shows all restuarants nearby your location with their company logos.

You can click on the restaurant logos for their current inspection hazard rating.

Clicking the rating will take you to the list page with the details of the restaurant location, the latest rating along, and a list of past hazard inspections.

## The List
Each restaurant will have the following information
  Name, Physical Address, Physical City, FacType, Latitude, and Longitude

Each inspection can be clicked on for further details including
  Inspection Date, Inspection Type, Critical or not Critical, Violation Details, and Hazard Rating
  
You can star the restaurants so that your favourites stay at the top of the list.
Favourited Restaurants will also appear with a star on the map.

You can search through the list by name, hazard rating, and so forth.
  
  
  
## Project Details  

The app is extremely simple to use. You can switch between the map and list with a simple click of a button.

Read Http url links to access CSV, and JSON data files.  

Stored and retrieved data inside android phones using InputStreams.

Builded UI layouts with working lists, dropdowns, buttons, toolbars, images, and many more.  

Worked in a 4 man agile team that experienced weekly iteration changes to the project. (Total of 3 iterations) 

Learned to adapt to changes, plan & test as a team, and catch bugs through formal/informal code reviews. 

Resolved Gitlab merging issues, and learned how to add, commit, push, and pull from gitlab repository. 

Experienced both techniques of Checkout-Edit-Merge and Lock-Edit-Unlock.
