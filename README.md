The App js file includes the following components which are essential:
- It includes essential imports for navigation functionality.
- The `Home` and `Login` screens are imported for navigation.
- A stack navigator is created to handle the app's navigation flow.
- The `App` component uses a `NavigationContainer` to encapsulate the navigator, which starts at the 'login' screen and has no header.
- Two routes, login and Home, are set up within the stack navigator.
- The navigation setup enhances user experience by providing a seamless transition between the login and home screens without a header bar.

  The Login js file also use the following components:
  - The LoginScreen component is for user login in a job app.
- It uses React's `useState`, native components, and `StatusBar`.
- State variables `name` and `email` capture user input.
- `handleLogin` navigates to the 'Home' screen with user data.
- The UI includes a `StatusBar`, text for app name and messages, `TextInput` for user details, a login button, social media login options, and a registration prompt.
- `styles` define the visual design of the components.
- The component offers a clear login process with manual and social media options, efficient input handling, and smooth navigation to the home screen after login.

 The `home.js` file is a React Native component for job listings. Home js file contains these components:
- It imports various components from 'react-native' and an icon component.
- Contains two data arrays with job details for listings.
- Features a `JobItem` component for displaying job information.
- The `App` component includes a scrollable view with headers, search functionality, and job sections.
- Styles are defined for UI components to enhance user experience.
- The file's design facilitates job searches and displays profiles, with efficient data rendering and a clean interface.

  
