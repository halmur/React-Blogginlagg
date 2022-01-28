Övningsuppgift - Blogginlägg (React + API)

Vid start av applikationen, hämta samtliga inlägg från följande API: https://jsonplaceholder.typicode.com/posts
För varje post, rendera en <Post/>-komponent med ett inlägg som visar ut dess titel och textinnehåll. Längst ner i varje post ska det finnas en knapp för att visa information om användaren som skrev inlägget.
När knappen klickas på ska komponenten <UserInformation/> renderas inuti <Post/>-komponenten.
När <UserInfo/> renderas, ska data för användaren hämtas från /users-endpointen i samma API med hjälp av det id som skrev inlägget (userId).

    (T.ex om inläggets userId är 3, hämtar du data från https://jsonplaceholder.typicode.com/users/3)

I <UserInfo>-komponenten ska du skriva ut användarens användarnamn, email samt stad.

Lycka till! /Brandon



<br>
<br>


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
