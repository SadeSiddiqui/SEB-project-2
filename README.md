# Future FurBaby 




## Table of Contents
- Introduction
- Features
- Future Enhancements 
- Installation
- Usage
- Technologies Used
- Testing 
- Contributions/Development Status 
- License and Acknowledgements 
- Contact Information 



## Introduction 
Future FurBaby is a two-page frontend application designed for cat enthusiasts to explore various cat breeds. It leverages a third-party API to fetch and display detailed information about a variety of cat breeds in a visually appealing and user-friendly format. The app includes a dynamic search feature with auto-suggestions and ensures a responsive design for both desktop and mobile views. 



## Features 
- Responsive Design: Ensures the application is accessible across different devices, including mobile, tablet, and desktop. 
- API integration: Fetches cat breed data from The Cat API. 
- TypeScript Type Safety: Ensures robust type-checking throughout the codebase. 
- Basic State Management: Uses React's ```useState``` and ```useEffect``` for managing component state and side effects.
- Dynamic Search with Auto-Suggestions: As users type in the search bar, they get instant suggestions matching their input.
- **Lazy Loading (via API)**: Dynamically loads more breeds as users scoll down, leveraging the API's built-in pagination to optimize performance and reducing loading times.



## Future Enhancements 
Potential future enhancements include:

- Error handling: Displays user-friendly error messages in case of API failure or network issues.
- Loading indicators: Implement visual indicators during API calls to enhance user experience.   
- User Authentication: Allows users to login and save their favourite breeds. 
- Advanced Pagination: Efficiently load and paginate cat breeds for better performance. 
- Multiple API integrations: Add other animal APIs (e.g dogs reptiles) for expanding browsing options.
- Booking software: Allows users to book appointments to meet or adopt specific breeds. This could be integrated with shelter or breeder databases and include calendar functionality to schedule meetings, either in-person or virtually.  
- Breed Comparison Tool: Enables users to compare characteristics of multiple breeds side-by-side. 
- Breed Voting System: Allows users to vote for their favourite breeds and display the most popular ones.   
- Advanced Filtering: Filter breeds based on temperament, size or other traits to help users find their ideal pet.



## Installation

1) First clone the repository to your local machine:
 
```git clone git@github.com:SadeSiddiqui/SEB-project-2.git```

```cd SEB-project-2```

Alternatively, if your unfamiliar with SSH, use HTTPS: 

```git clone https://github.com/SadeSiddiqui/SEB-project-2.git```

```cd SEB-project-2```

2) Install Dependencies:

After you've cloned the repo, install all the necessary packages: 

```npm install```

```npm install bulma react react-dom react-router-dom```

```npm install --save-dev @types/react @types/react-dom @types/react-router-dom @vitejs/plugin-react sass typescript vite```

3) Running the development server: 

To start the development server, run the following command: 

```npm run dev```



## Usage  
### Project Structure 

The main source code of this project is located in the ```src``` folder as follows: 

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
### Main Components: 

- ```App.tsx```: Main component that sets up routing and renders the app. 
- ```Home.tsx```: Display the homepage content, including the cat breed list. 
- ```Navbar.tsx```: Navigation bar allows users to switch between views.  
- ```Catbreeds.tsx``` and ```Catcards.tsx```: These handle fetching and displaying the cat breeds.

### Styling: 

All styling is handled in ```styles/main.scss```. Modify this file to make changes to the appearance and user experience of the the app.



## Technologies Used  

- React: JavaScript library for building user interfaces.
- TypeScript: Superset of JavaScript providing static type definitions.
- Vite: Modern build tool for faster development. 
- Node.js and NPM: Package installation and management tools. 
- Bulma: CSS framework for responsive design and layout. 
- SASS: CSS preprocessor for easier styling. 
- Git & Github: Version control and project collaboration tools



## Testing 

Although this project doesn't include automated tests, it was manually tested for functionality. Future improvements could involve: 

- Unit tests for individual components using Jest.
- End-to-end tests using Cypress to simulate user interactions. 


## Contributions/Development State   

This project is currently in its MVP state and it was collaborated with Evyn-Rose Goldstein [evynrose](https://github.com/evynrose). If you would like to contribute follow these steps: 

1) Fork the repo: Click on the ```Fork``` button at the top-right corner of the GitHub repository, to create your own personal copy of the repo on your GitHub.

2) Clone the repo:

```git clone https://github.com/your-username/SEB-project-2.git``` 

3) Create a branch:

```git checkout -b feature-branch-name```

4) Make changes and commit: Add features or fix bugs. 

5) Commit and push:

```git commit -m "Description of changes"```

```git push origin feature-branch-name```

6) Open a Pull request:
  1. After you have pushed your changes onto your fork go to the original GitHub repo click on ```pull request```. 
  2. Click ```base``` this will give you the option on which branch you want to merge your branch with this is usually the ```main``` or ```master```.
  3. Then click on the ```compare``` button next to it select your branch that has the changes you added.
  4. Click ```New pull request``` and , and GitHub will show you the changes you made review you are happy with them and submit them.



## License and Acknowledgements

Licensing: This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

Acknowledgements: A big thank you to collaborator Evyn-Rose Goldstein [evynrose](https://github.com/evynrose) with her help in this project and thanks to That API Company for providing the Cat API.



## Contact Information

Feel free to reach out for questions or collaboration opportunities: 

Syed Siddiqui: 

[LinkedIn](https://www.linkedin.com/in/syed-siddiqui/)

[Email](syedsiddiqui1@gmail.com)

Evyn-Rose Goldstein: 

[LinkedIn](https://www.linkedin.com/in/evynrose/)
