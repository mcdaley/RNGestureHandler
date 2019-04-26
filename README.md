# RNavigationDemo
An example React Native app that demonstrates how to use React Navigation
to setup the layout for an app. The app provides a basic layout with tabs
and also a settings section for managing a user's profile.

The layout can be used to quickly get started building a new app with
basic core layout, so you can focus on building the app logic.

## Layout

### Tab Navigation
Users can navigate to different sections of the app by clicking on the
bottom tabs. Each tab is implemented using **stack navigation**, so users
can drill down on the screens in each tabbed section.

### Stack Navigation
The sections of the app are broken down into **stacked** screens, so 
users can drill down to the details of each section.

### Settings Navigation
Most apps have a section for managing the user profile. Since settings
navigation is separate from the main app navigation, the settings
navigation is built using the SwitchNavigator. When a user clicks on the
gear then the user is directed to the __Settings__ navigation. The user
can click the **Done** button to navigate back to the __App__ navigation.

## To Do
* Add Authentication navigation flow
  - Sign Up
  - Sign In
  - Forgot Password
* Centralize styling
* Header Formats
  - Search Window and link to url/uri.
* Add Modal screen

## To Do
* Figure out how to add the default header to the createBottomTabNavigator
  section. I have added the header styling to the createStackNavigation, which
  is OK for now.

