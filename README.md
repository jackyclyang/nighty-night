# Nighty Night

## Overview

_**Nighty Night** is a web application that helps you get ready for bedtime by clearing your mind and reducing anxiety. By using the product, you will get the distractions out of your mind and gain the peacefulness desired for a good night sleep. 


<br>

## MVP

_The **Nighty Night** MVP allows users to create accounts. And with that account, the user can write down great things happening that day and why before bedtime. Research has shown that it helps reduce anxiety and depression. In additon, the user can jog down a to-do list for the following day, which helps people get out any distractions out of their minds. You can have it set, and don't have to worry about what should be done anymore (which really negative impacts your sleep quality). The app will save everything and remind you the next morning. The MVP will also include the reward badge system as well as a list of white noise soundtracks and promote mindfulness. 

<br>

### Goals

- Create account
- Sign in/Sign out
- Write down great things happening that day (text, image)
- Check out the history of great things
- Write down to-do list for the following day (text, image)
- Send out email reminder of the to-do list the next morning
- A reward badge system
- Soundscape: a list of soothing soundtracks (including favorites feature)


<br>

### Libraries and Dependencies


|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | Front-end component framework |
|   React Router   | Front-end library to set up routes and links |
|      Axios       | Render API from backend |
|      Rails       | Back-end framework with Ruby |

<br>

### Client (Front End)

#### Wireframes


![Dummy Link](url)

- Desktop Landing


![Dummy Link](url)

- Desktop Dashboard



#### Component Tree


#### Component Hierarchy


``` structure

src
|__ assets/
      |__ images
|__ components/
      |__ Header.jsx
      |__ Home.jsx
            |__ Sign up.jsx
            |__ Sign in.jsx
      |__ Main.jsx 
            |__ Dashboard.jsx
                  |__ Badges.jsx
                  |__ Reminder.jsx
            |__ ToDo.jsx
                  |__ ToDoListForTmr.jsx
                  |__ ToDoCalendar.jsx
            |__ GreatThings.jsx
                  |__ GreatThingsToday.jsx
                  |__ GreatThingsCalendar.jsx
            |__ Soundscape.jsx
                  |__ Soundtrack.jsx
                  |__ Favorites.jsx
            |__ UserProfile.jsx
                  |__ Badges.jsx
                  |__ Settings.jsx
      |__ About.jsx
|__ services/

```

#### Component Breakdown


|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | functional |   n   |   n   | _The Header will contain the navigation and logo._               |
|     Home     |   class    |   y   |   y   | _The Home will be the homepage including login and signup._      |
|  Dashboard   |   class    |   y   |   y   | _The Dashboard will be the landing page after user sign in._     |
|     ToDo     |   class    |   y   |   y   | _The ToDo will allow users to create/read/update/delete their to do list for the next day._      |
| GreatThings  |   class    |   y   |   y   | _The GreatThings will users to create/read/update/delete great things happening on the day_      |
|  Soundscape  |   class    |   y   |   y   | _The Soundscape will contain soundtracks of natural soothing sounds_      |
| UserProfile  |   class    |   y   |   y   | _The UserProfile will contain user information with CRUD actions as well as Badges_      |
|    About     | functional |   n   |   n   | _The About will explain what this app does and why_      |


#### Time Estimates


| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Back-end setup      |    H     |     10 hrs     |       -       |     TBD     |
| Seed data           |    M     |     4 hrs      |       -       |     TBD     |
| Services setup      |    H     |     6 hrs      |       -       |     TBD     |
| Header              |    L     |     1 hrs      |       -       |     TBD     |
| Home Page           |    H     |     2 hrs      |       -       |     TBD     |
| Dashboard           |    H     |     4 hrs      |       -       |     TBD     |
| ToDo List CRUD      |    H     |     10 hrs     |       -       |     TBD     |
| Great Things CRUD   |    H     |     10 hrs     |       -       |     TBD     |
| Soundscape          |    H     |     6 hrs      |       -       |     TBD     |
| User Profile (CRUD) |    H     |     10 hrs     |       -       |     TBD     |
| About               |    L     |     4 hrs      |       -       |     TBD     |
| Additional Styling  |    L     |     4 hrs      |       -       |     TBD     |
| Deployment          |    H     |     1 hrs      |       -       |     TBD     |
| TOTAL               |          |     72 hrs     |       -       |     TBD     |



<br>

### Server (Back End)


![#### ERD Model](https://res.cloudinary.com/dvmkqx6v1/image/upload/v1594614315/Night_ERD_pnsoik.png)

<br>

***

## Post-MVP

***
- Add an onboarding stepper that introduces new users to the app
- Add additional contents that can help faciliate a better nighttime environment (e.g. ASMR, Bedtime stories, Bedtime Routine Tips)

## Code Showcase



## Code Issues & Resolutions


