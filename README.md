# SEI Project Two: Yu-Gi-Oh!

## Table of Contents:

|  **No:**     | **Content** |
| -------- | ------- |
|    1    | **`Project Overview`**|
|    2     | **`The Brief and Technical Requirements`**|
|    3    | **`Technologies Used`**|
|    4     | **`Project Timeline - 2 Days`**|
|    5     | **`Bugs`**|
|    6     | **`Wins and Challenges`**|
|    7     | **`Future Improvements`**|
|    8     | **`Key Learning`**|

 ## 1. Project Overview
This was a pair coding project, where we were briefed to **build a React application** that consumes a **public API**. My coding partner and I both had to decide on a common theme for the project. We both made a list of interests we had and from that we both had a common interest in Yu-Gi-Oh and decided to use the Yu-Gi-Oh API to build a website.

<img width="1866" alt="Screenshot 2021-12-14 at 16 55 42" src="https://user-images.githubusercontent.com/88886169/146043756-d5f8dc86-e23a-4421-ae6c-d7d6099bf3de.png">

#### Deployed version available here: 👉🏽👉🏽[*Yu-Gi-Oh!*](https://isaac-kumar-yugioh.netlify.app/) 👈🏽👈🏽

### Resources:
> The following websites assisted with this project:
> 1. [React](https://reactjs.org/)
> 2. [Some free APIs](https://apilist.fun/)
> 3. [Some more free APIs](https://github.com/public-apis/public-apis)
> 4. [Even more free APIs](https://dev.to/camerenisonfire/10-intriguing-public-rest-apis-for-your-next-project-2gbd)

## 2. Project Brief and Technical Requirements

- **Consume a public API**
- **A working application hosted on the browser**
- **Have several components**
- **The app can have a router**
- **Include wireframes**


## 3. Technologies Used

- React.js
- JavaScript (ES6)
- HTML5
- CSS
- Bulma- CSS Framework 
- Animate.css
- Axios
- Git
- GitHub
- Google Fonts
- Fisma- Wireframe
- Insomnia- REST Client
- Yarn


## 4. Project Timeline- 2 Days

### Planning:
The first day was spent finding a common interest between my coding partner and I. It was then a matter of reviewing and breaking down the dataset/type we would receive from the API. The data was tested in Insomnia to make sure the requests were working correctly. We looked into different endpoints to see which one we would need and how we could manipulate them to display on the frontend.

<img width="1514" alt="Screenshot 2021-12-14 at 17 17 45" src="https://user-images.githubusercontent.com/88886169/146047645-19e09a57-2927-4984-a311-ed6b8d13e365.png">

Once we were comfortable with the dataset it was then time to create a wireframe of the components and how they would all relate to each other. We wanted a homepage with a search functionality as well as three card categories (monster, spell and trap) displaying a variety of cards on different pages. Each card within the selected category would then be clickable so that the user is taken to a seperate page where they can read up on the details of the specific card they clicked.

<img width="976" alt="Screenshot 2021-12-14 at 17 32 45" src="https://user-images.githubusercontent.com/88886169/146049877-8d95f00d-38c6-4cd0-856d-d17cb437e0d3.png">

### Getting Started:
We started coding our project by creating the app using the command `npx create-react-app APP_NAME --template cra-template-ga-ldn`, adding the origin of our repo name to GitHub and pushing up. Then once inside the app we installed `yarn` and then typed in the command `yarn start` to run the server. We then installed `Bulma`, `React Router Dom`, `Axios` and `Animate.css` as these were the dependencies we needed.

### Components:

Once we had installed our dependencies for the project we started building out the different components we needed, as per our wireframe. 

**Navbar:** We used Bulma to assist us in obtaining a Navbar component which we felt was suitable for our website and then began adding the home, random and wishlist buttons. Once these buttons and the background of the Navbar component was designed, we began by chaining a get request to get the three different category of cards. We were then able to create a nested onClick function that firstly randomised a card from one of the three categories and then sent the user to a specific page showing the id of the card. 

<img width="1504" alt="Screenshot 2021-12-14 at 18 08 51" src="https://user-images.githubusercontent.com/88886169/146055427-6f151085-6f19-49a4-8f21-b927092f4414.png">

**Homepage:** We bagan creating the homepage by adding a background using CSS, three buttons (one for each card category) and a search bar. We then built out the homepage by using `Link` import from `react-router-dom` to navigate to the three card category pages. For finishing touches, we added some animations to the buttons.

<img width="1899" alt="Screenshot 2021-12-14 at 18 18 54" src="https://user-images.githubusercontent.com/88886169/146056938-92f152e0-c97c-4036-a61a-00d83f5d4c72.png">

**Monster, Spell & Trap pages:** 



## 5. Bugs

- 
- 

## 6. Wins and Challenges

### Wins:
- 
- 
- 

### Challenges:
- 
- 

## 7. Future Improvements

- 
- 
- 
- 
- 


## 8. Key Learnings

- 
- 
- 
- 
- 




