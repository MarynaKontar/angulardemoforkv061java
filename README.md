# Angulardemoforkv061java

Demo angular project for KV-061.java group of SoftServe academy.
#####I. To manage existing angular project or create new angular project your need to have on your computer:
1. Install Node.js - javaScript runtime on Chrome javaScript engine

      `sudo apt install nodejs`

2. check npm (node package manager) version (we need it to install angular cli):
      
      `npm --version` 

    If there isn't npm, install it:

      `sudo apt install npm`

3. Install angular cli - angular command line interface; we need it to start new angular project and managed it.

      `sudo npm install @angular/cli -g`

(You can find how to install angular in the first lecture of https://www.udemy.com/course/angular-5/  free course. It lasts less than 4 minutes)

#####II. Clone this project to your computer.
#####III. Run the project on your computer:
- navigate to the folder of cloned project

     `cd /where/your/clone/this/project/angulardemoforkv061java`

- run the project on your computer

     `ng serve`
      
Navigate to `http://localhost:4200/`, where your can see standard angular first page or what your wrote in .../angulardemoforkv061java/src/app/app.component.html.

#####OR
#####II. Create your own angular project:
  If you want create your own angular project, write next command in terminal (after 1-3 points of I.):

- navigate to the folder where you want to create a project 

    `cd /where/your/want/to/save/project`

- create angular project with "angulardemoforkv061java" name (for example), styles in .scss files and routing module:

    `ng new angulardemoforkv061java --style=scss --routing`
      
- navigate to created project folder:

    `cd angulardemoforkv061java`
      
- run the project on your computer:

    `ng serve`

Navigate to `http://localhost:4200/`, where your can see standard angular first page or what your wrote in .../angulardemoforkv061java/src/app/app.component.html.

  


Other commands to be used in the project:
 - generate components:
`ng g c header`
`ng g c admin`
`ng g c customer-account`
`ng g c registration`
`ng g c map`

 - add modules:
 
 FormsModule
 
 HttpClientModule
 
 AgmCoreModule.forRoot({
       apiKey: 'AIzaSyDZi0wYlp1tFojFhnEeNc8bsGlHiiawYwU'
     })
 
  - add Google Maps:
  `cd /where/your/your/project/angulardemoforkv061java`
  `npm install -- save @agm/core`
 


Useful links:

 - Get an API Key for Google Maps:

https://developers.google.com/maps/documentation/javascript/get-api-key

 - Angular – Display Current Location Using Google Map:

https://www.codementor.io/@brijmcq/angular-display-current-location-using-google-map-fnl3tosdq

