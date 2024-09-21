# Future FurBaby 

 

## Table of Contents
- Introduction
- Features
- Future Enhancements 
- Installation
- Usuage
- Technologies Used 
- Contributions/Developement Status 
- Code Examples/Explaination of Key Sections
- License and Acknowledgements 
- Contact Information 


## Introduction 
Future FurBaby is a two-page frontend application that tailored to cat enthusiast to browse through multiple cat breeds. This application has leverages a third-party API to access and display information about a varity of cat breeds, it then displays this on frontend is a visually appleasing and user-friendly display and it also leverages responsive design on the frontend, specifically in the styles.css file, to display this application on mobile as well. 

## Features 
- Responsive Design
- API integration
- TypeScript Type Safety
- Basic State Management 
- Dynamic Search with Auto-Suggestions
- **Lazy Loading (via API)**: The project dynamically loads more breeds as the user scrolls down, leveraging the API's built-in pagination to optimize loading times.

## Future Enhancements 
If further development were to be done on this project, the following features could be implemented:

- Error handling for API requests, when there are networking errors or API failed requests it will display a message saying there has been a problem with your request or connection.  
- Loading indicators, while the pages are loading it will display a symbol while making network connections.  
- User Authentication, this will enable users to create and login into accounts on the websites and save certain breeds they were previously looking at.
- Pagination/Lazy Loading, this will enable the website to load more sets of cat breeds efficiently, improving performance and UX.
- Multiple API integrations, using multiple API's such as dog API's, reptile API's etc to display multiple animals for users to browse.
- Booking software, this will allow the user to book a 30 minute window with the their desired breed to confirm their adoption.
- Breed Comparison Tool, this will allow users to compare characteristics between multiple breeds side-by-side.
- Breed Voting System, this will allow users to vote for their favorite breeds and display the most popular breeds in real time.
- Advanced Filtering Options, add extra filters to search by traits like temperament, size, or origin to help users find the breed that fits their preferences.  

## Installation
Clone this repository:  
- git clone git@github.com:SadeSiddiqui/SEB-project-2.git
- cd SEB-project-2
  
You have to set up SSH keys to clone this repo onto your computer, but if you are not familiar with SSH keys then use the instructions below:

- git clone https://github.com/SadeSiddiqui/SEB-project-2.git
- cd SEB-project-2

Install Dependices:
Run the following commands to install all the packages

- npm install
- npm install bulma react react-dom react-router-dom
- npm install --save-dev @types/react @types/react-dom @types/react-router-dom @vitejs/plugin-react sass typescript vite

Running the developement server: 
To start the project run the following npm command in the terminal

- npm run dev 

## Usuage  
Project Structure: The main source code of this project is located in the ```src``` folder, the image below shows a folder tree of the ```src``` folder including the files and their purposes. 

``` src/
├── components/
│ ├── Catbreeds.tsx      # Displays a list of cat breeds
│ ├── Catcards.tsx       # Renders individual cat breed cards
│ ├── Home.tsx           # Home page layout
│ └── Navbar.tsx         # Navigation bar for routing between pages
├── App.tsx              # Root component of the application
├── main.tsx             # Entry point to bootstrap the app
├── styles/
│ └── main.scss          # Global styles and theme configurations
├── photos/              # Directory containing images used in the app
├── d.ts                 # TypeScript declaration files for type definitions
```
TypeScript Components: 

- ```App.tsx``` This is the main component of the project that sets everything up in the application. Modify this file to change how components are rendered 
- ```Home.tsx``` This is the inital view of the project 
- ```Navbar.tsx``` This handles navigation between different views and routes in the project 
- ```Catbreads.tsx``` and ```Catcards.tsx``` These two files are responsible for displaying the cat information 

Styling: 

The styles are defined in ```styles/main.scss```. Update this file if you want to make changes to the appreance and engagment of the project  


## Technologies Used  

- React (frontend)
- TypeScript (strong typing)
- Node.js and NPM (package management)
- Git and Github (version control)

## Contributions/Developement State   

This project was in collaboration with evynrose Evyn-Rose Goldstein. Contributions are welcome to contribute

- Fork the repo: Click on the ```fork``` button to create your own personal copy of the repo on your GitHub.
- Clone the repo: Instructions for cloning the repo is on top of the Installation section 
- Create a branch: Create a branch using the this code in git ```git checkout -b feature-branch-name```
- Make changes and commit: Once you've made your changes to your local copy commit the changes you made, you can do this with this code ```git commit -m "Description of changes"```
- Push the changes: After the made and committed the changes push your branch back into the for, you do this with this code ```git push origin feature-branch-name```
- Open a Pull request:
  1. After you have pushed your changes onto your fork go to the original GitHub repo click on "pull request" then click "New pull request" and click base this will give you the option on which branch you want to merge your branch with this is usually the main or master, in the compare button next to it select the branch you created that has the changes you added. GitHub will show you the changes you made review you are happy with them and them 


## Code Examples/Explaination of Key Sections

## License and Acknowledgements

## Contact Information
