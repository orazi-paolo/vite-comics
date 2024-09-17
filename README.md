# DC Comics Test Web Page
This project is a copy of an old DC Comics web page and was made to practice using Vue.js components and props. It includes a header, main section and footer, implemented using Vue components broken down as follows.
## Project structure
### 1. AppHeader
Contains the DC Comics logo and a horizontal navigation menu with the following links:
- Characters
- Comics 
- Movies
- TV 
- Games
- Collectibles
- Videos
- Fans
- News
- Shop

This section allows users to easily navigate between the different contents of the site if there are any.
### 2. AppMain
The main section is managed by the AppMain component, which in turn is divided into other components to organize the content:
#### 2.1 AppMainJumbotron
The component represents the background image at the top of the page and the button for the Current Series.
#### 2.2 AppMainCurrentSeries
This component contains a grid of comic book covers, each with the series title.
#### 2.3 AppMainFeatureSection
Here you will see a blue bar with icons and links to various services.

### 3. AppFooter
The footer is managed by the AppFooter component and is divided into several informative sections:
- DC Comics
- DC
- Sites
- Shop
#### 3.1 AppFooterSignUpNavbar
In the footer we find the following component that includes a "Sign Up Now" button that could be used to register, as well as links to DC Comics' social media profiles.

## Functionality
The project was built using the following technologies:
- HTML
- CSS
- SCSS
- JS
- Vue.js

