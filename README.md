# Car-Dealership-and-Rental-application

<!--- The following README.md sample file was adapted from https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md by Gabriella Mosquera for academic use --->

- ## Built a website for solving customer problems related to car maintenance and rental using the MERN stack and deployed the application on Heroku. Used REST APIs to fetch and post data. 
- ## Designed a customer and dealer centric web application with a group of 5 people which acts as a one stop solution for customers to buy, service, rent cars and book test drives.


## Authors

- [Adarsh Kannan Iyengar](adarsh.kannan@dal.ca) - _(Developer)_
- [Elizabeth James](elizabeth.james@dal.ca) - _(Developer)_
- [Harsh Hariramani](hr951414@dal.ca) - _(Developer)_
- [Krishna Sanjaybhai Jadav](krishna.jadav@dal.ca) - _(Developer)_
- [Tuan Hamid](tn220771@dal.ca) - _(Developer)_
- [Leah Isenor](leah.isenor@dal.ca) - _(Developer)_

## Credentials

- Credentials for employees<br/>
  _username_ : sl.rahmanhamid@gmail.com<br/>
  _password_ : 12345678

- Credentials for customers<br/>
  _username_ : tn220771@dal.ca<br/>
  _password_ : 12345678

- _Date Created_: 16 June 2022
- _Last Modification Date_: 15 JUL 2022
- _Live frontend_: <https://project-group9-frontend.herokuapp.com/>
- _Backend API_: <https://group9-backend.herokuapp.com/>
- _Git URL_: <https://git.cs.dal.ca/lisenor/5709_group9/-/tree/main>
- _Backend Git URL_: <https://git.cs.dal.ca/jadav/5709_cardealerbackend_group9>


## Built With

- [React](https://reactjs.org/) - The web framework used
- [MUI](https://mui.com/material-ui/getting-started/overview/) - UI Component Library
- [NodeJS](https://nodejs.org/en/) and [ExpressJS](https://expressjs.com/) - For hosting the application server

## Sources Used


_FileName_: carFrom.js<br/>
_line_: #70 and #79<br/>
_why_: I need to select date in my form<br/>
_how_: I referred to the user guide and its properties<br/>
_source_: https://www.npmjs.com/package/react-date-picker<br/>

_FileName_: carResults.js<br/>
_line_: #40 to #45<br/>
_why_: to display the list in pretty format,make use of pagination buttons and sort icons, make the list searchable, make the list sortable<br/>
_how_: reffered code samples and usages to understand the usage of material table.The car component's properties were used in the material table tag<br/>
_source 1_: https://blog.logrocket.com/material-table-react-tutorial-with-examples/<br/>
_author_: Mohammad Fasil<br/>
_source 2_: https://material-table.com/#/ (official documentation)<br/>
_source 3_: https://mui.com/material-ui/react-progress/ - circular progrss bar used at line #45 of CarMoreDeals.js
_source 3_: https://stackoverflow.com/questions/63647493/react-material-table-is-not-displaying-table-icons <br/>
_author_: Jimi D<br/>

_FileName_: CarMoreDeals.js<br/>
_line_ : #45<br/>
_why_: show progress bar until the results are loaded<br/>
_source_: https://mui.com/material-ui/react-progress/<br/>

_FileName_: rental.controller.js (backend proj)<br/>
_line_ : #75<br/>
_why_: convert Date to string in YYYY-MM-DD:<br/>
_source 4_: https://stackoverflow.com/questions/23593052/format-javascript-date-as-yyyy-mm-dd
_Author_: Darth Egregious

_FileName_: Carform.js, CarResults.js, TableIcons.js, CarLoan.js
These were implemented as part of CSCI 5709 Assignment 1 and 3 by Elizabeth James
These include Feature 1: Car Rentals and Feature 2: Car Loans
<br/>

https://mui.com/material-ui/react-progress/ - circular
used at line #45 of CarMoreDeals.js

      The code above was created by adapting the code in [App bar React component - Material UI](https://mui.com/material-ui/react-app-bar/) as shown below:



- <!---How---> The code in [App bar React component - Material UI](https://mui.com/material-ui/react-app-bar/)  was implemented to be the navigation bar of my website
- <!---Why---> [App bar React component - Material UI](https://mui.com/material-ui/react-app-bar/) 's Code was used because it shows how the library works in creating the navigation bar
- <!---How---> [App bar React component - Material UI](https://mui.com/material-ui/react-app-bar/) 's Code was modified by making changes to the required navigation buttons and dropdown menu. Also a suitable logo replacement icon was taken from MUI Icon pack at https://mui.com/material-ui/material-icons/

The code above was created by adapting the code in [MUI](https://mui.com/x/react-data-grid/) as shown below:

```
<DataGrid
        rows={rows}
        columns={columns}
        pageSize={5}
        rowsPerPageOptions={[5]}
        checkboxSelection
        disableSelectionOnClick
      />
```

- <!---How---> The code in [MUI](https://mui.com/x/react-data-grid/) was implemented by using it for employee list
- <!---Why---> [MUI](https://mui.com/x/react-data-grid/)'s Code was used because it shows how to create data grid
- <!---How---> [MUI](https://mui.com/x/react-data-grid/)'s Code was modified by adding custom id and fields


## Image credits

### src/pages/services/assets/testdrivecar.png, src/pages/services/dealer/assets/testdrivecar.png

"2022 Toyota Agya 1.2 G GR Sport B101RA (20220317) 01" by オーバードライブ 83 is licensed under CC BY-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/?ref=openverse.

### src/pages/services/assets/repairscar.png, src/pages/services/dealer/assets/repairscar.png

"2022 Hyundai Atos 1.1 Plus" by RL GNZLZ is licensed under CC BY-SA 2.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/2.0/?ref=openverse.

### src/mocks/carLoanStub.js, src/mocks.carStub.js

Toyota: https://www.drivespark.com/images/2021-01/toyota-fortuner-exterior-1.jpg <br/>
Mercedes: https://cdn.motor1.com/images/mgl/7xQZW/s1/2021-mercedes-amg-gt-stealth-edition.jpg <br/>
Innova: https://gaadiwaadi.com/wp-content/uploads/2022/04/Toyota-Innova-next-gen-rendered-img1-1068x601.jpg <br/>
Suzuki: https://s1.cdn.autoevolution.com/images/models/SUZUKI_Swift-5-Doors-2020_main.jpg <br/>

### src/vehicles/CustomerForm.js

LockoutlinedIcon logo: https://mui.com/material-ui/getting-started/templates/sign-in/ & https://mui.com/material-ui/material-icons/

### Accessories remote images
https://www.flickr.com/photos/jeepersmedia/14061604449
https://www.flickr.com/photos/jeepersmedia/14061639880/in/photostream/
https://www.flickr.com/photos/jeepersmedia/14061639170/in/photostream/
https://www.flickr.com/photos/jeepersmedia/14268423653/in/photostream/

https://pxhere.com/en/photo/1548209
https://www.shutterstock.com/image-photo/1463332910?utm_source=iptc&utm_medium=googleimages&utm_campaign=image

https://www.flickr.com/photos/chdot/2694946585
https://commons.wikimedia.org/wiki/File:OBD_Auto_Scanner_connecting_to_the_ECU.JPG

https://www.flickr.com/photos/concavowheels/8383098766
https://commons.wikimedia.org/wiki/File:Prestone_AMAM_5050_with_Superiority_Claim.jpg
## Acknowledgments

https://pixabay.com/photos/bottle-container-engine-oil-liquid-3108641/ for the creative commons image used
https://www.lipsum.com/ for lorem ipsum generator
