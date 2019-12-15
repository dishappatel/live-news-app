# Live News Web App

This live news web application is created using Angular JS and Material Design. The application fetches real time news using NEWS API and renders the content using material design.

NEWS API - [https://newsapi.org/](https://newsapi.org/)

This application is created with the help of Rachid Sakara's [blog](https://www.smashingmagazine.com/author/rachid-sakara/).

- Home Page
![Home Page](https://github.com/dishappatel/live-news-app/raw/master/screenshots/mainpage.png)
- Menu bar
![Menu bar](https://github.com/dishappatel/live-news-app/raw/master/screenshots/menubar.png)

# Pre-requisites
To run the app on your workstation, you need to have
-   [Node.js](https://nodejs.org/en/)  and npm installed;
-   [Angular CLI](https://cli.angular.io/)  installed.


# How to run
- Clone the repo
- Navigate to the directory `$cd live-news-app`
- Get the NEWS API from the [https://newsapi.org/](https://newsapi.org/) and paste it into `app/news-api.service.ts (line#9)`
- Run the app `ng serve`
- Open `localhost:4200` on your browser