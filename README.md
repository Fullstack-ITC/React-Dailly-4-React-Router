# React Router Navigation Exercise

## Objective
Practice setting up routing in a React application, creating multiple pages, using NavLink for navigation, and dynamically navigating users using the `useEffect` hook.

## Instructions

### Setup and Basic Routing
- Install `react-router-dom` using npm or yarn.
- Set up the basic routing structure inside your App component.
- Create three pages: `HomePage`, `AboutPage`, and `UserProfilePage`.

### NavLink for Navigation
- Create a `Navbar` component that will be displayed on every page.
- Inside the `Navbar`, set up `NavLink` components to navigate between the `HomePage`, `AboutPage`, and `UserProfilePage`. Ensure that the active link is styled differently (hint: use the `activeClassName` prop).

### Dynamic User Profile Page
- The `UserProfilePage` should display information about a user based on their user ID.
- Set up a dynamic route such as `/user/:userId` to handle displaying profiles based on the `userId` parameter.
- Display basic user information like Name and Email. For simplicity, you can hardcode a few user profiles in a mock data object.

### Dynamic Navigation with `useEffect`
- On the `HomePage`, display a button labeled "Go to Random User Profile".
- When this button is clicked, programmatically navigate the user to a random user's profile page.

## Bonus
- Implement a 404 Not Found page and display it when users navigate to a route that doesn't exist.
- Enhance the `UserProfilePage` to fetch user data from an API (you can use mock APIs like JSONPlaceholder) instead of using hardcoded data.
