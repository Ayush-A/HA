# HA
Himpact Assesment

Angular Assignment:

Build a production-ready angular single-page app, which has a dropdown with a list of users sorted in Alphabetical order. ( Use API 1)

On click of one of the items display the user details on a new page as label and value ( Use API 2)

Use separate components for dropdown and display of user details

 

                                API 1:https://reqres.in/api/users?page=1

                                API 2:https://reqres.in/api/users/<id>
                               
# Approach

ng new HIMPACT_Assesment
cd HIMPACT_Assesment

npm i --force
npm run start 
ng serve*

# modules used 
BrowserModule,
AppRoutingModule
HttpClientModule
MatSelectModule
BrowserAnimationsModule

# App rounting 
to loop the two api service

# Create Two Seperate Component -  Drop Down, User details 
use http module to request the api to fetch the data and pass the value (service - Api calliing 1. get user(),  Displayuser()) 


# component Dropdown 

fetching the date and putting into array userlist = any= []

ngoninit : nitialize the directive/component after Angular first displays the data-bound properties and sets the directive/component's input properties/

void function : user ddata
put into log file 
sort the data unto aplhabetical order 
pass the value of sorted data as id

# Component 
get the value as {id}, put into log file 
call the function displaydata{id}
