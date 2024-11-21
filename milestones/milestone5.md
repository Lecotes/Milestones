# Milestone 5

This document should be completed and submitted during **Unit 9** of this course. You **must** check off all completed tasks in this document in order to receive credit for your work.

## Checklist

This unit, be sure to complete all tasks listed below. To complete a task, place an `x` between the brackets.

- [X] Deploy your project on Railway
  - [X] In `readme.md`, add the link to your deployed project
  - [X] ***The link to the deployed project is: "[click here](https://lecotes.onrender.com/)"***
- [X] Update the status of issues in your project board as you complete them
  - [X] ***All milestones are 100% complete, visit [milestones here](https://github.com/Lecotes/Codebase/milestones)***
- [X] In `readme.md`, check off the features you have completed in this unit by adding a ✅ emoji in front of their title
  - [X] Under each feature you have completed, **include a GIF** showing feature functionality
- [X] In this document, complete the **Reflection** section below
- [X] 🚩🚩🚩**Complete the Final Project Feature Checklist section below**, detailing each feature you completed in the project (ONLY include features you implemented, not features you planned)
- [X] 🚩🚩🚩**Record a GIF showing a complete run-through of your app** that displays all the components included in the **Final Project Feature Checklist** below
  - [X] Include this GIF in the **Final Demo GIF** section below

## Final Project Feature Checklist

Complete the checklist below detailing each baseline, custom, and stretch feature you completed in your project. This checklist will help graders look for each feature in the GIF you submit.

### Baseline Features

👉🏾👉🏾👉🏾 Check off each completed feature below.

- [X] The project includes an Express backend app and a React frontend app
  - [X] ***[Express backend](), [React frontend](https://github.com/Lecotes/frontend_deploy)***
- [X] The project includes these backend-specific features:
  - [X] At least one of each of the following database relationship in Postgres
    - [X] one-to-many
      - [X] ***Check [here](https://github.com/Lecotes/backend_deploy/blob/main/resetDatabase.js) (e.g., a user can have many friends)***
    - [X] many-to-many with a join table
      - [X] ***Check [here](https://github.com/Lecotes/backend_deploy/blob/main/resetDatabase.js) (e.g., many annotations can have many replies)***
  - [X] A well-designed RESTful API
    - [X] The API can respond to at least one of each type of request: GET, POST, PATCH, and DELETE
      - [X] ***Fetch text, post text, edit annotations and comments, delete text annotations or replies***
    - [X] Routes follow proper naming conventions
  - [X] The ability to reset the database to its default state
    - [X] ***Check resetDatabase.js [here](https://github.com/Lecotes/backend_deploy/blob/main/resetDatabase.js)***
- [X] The project includes these frontend-specific features:
  - [X] At least one redirection
    - [X] ***Redirect to login, signup, dashboard and text with ids***
  - [X] At least one interaction that the user can initiate and complete on the same page without navigating to a new page
    - [X] *****Add highlight annotations and replies*****
  - [X] Dynamic frontend routes created with React Router
    - [X] ***For each text, there is a "text/:id" route created***
  - [X] Hierarchically designed React components
    - [X] Components broken down into categories, including Page and Component types
    - [X] Corresponding container components and presenter components as appropriate
      - [X] ***We also divided things by creating modals and submission boxes.***
- [X] The project includes dynamic routes for both frontend and backend apps
- [X] The project is deployed on Railway with all pages and features working
  - [X] ***Deployed on Render since Railway no longer offers a free trial, you can reach the deployed project [here](https://lecotes.onrender.com/)***

### Custom Features

👉🏾👉🏾👉🏾 Check off each completed feature below.

- [X] The project gracefully handles errors
  - [X] ***Try catch blocks are implemented, errors are returned***
- [ ] The project includes a one-to-one database relationship
- [X] The project includes a slide-out pane or modal as appropriate for your use case
  - [X] ***There are text-add modals, and add-friend modals***
- [X] The project includes a unique field within the join table
  - [X] ***annotation_votes and reply_votes tables include UNIQUE usernames to prevent the same user from voting more than once***
- [ ] The project includes a custom non-RESTful route with corresponding controller actions
- [X] The project allows filtering and/or sorting as appropriate for your use case
  - [X] ***Users can filter other users to add friends or share files, and filter their own files to go to a file quicker***
- [X] Data is automatically generated in response to a certain event or user action. Examples include generating a default inventory for a new user starting a game or creating a starter set of tasks for a user creating a new task app account
  - [X] ***For any annotation, we have prefilled fields such as the username attached to each annotation***
- [X] Data submitted via a POST or PATCH request is validated before the database is updated
  - [X] ***For the voting system, we check the patch and post for each vote for unique user. If the user has already voted, we prevent them from voting again***

### Stretch Features

👉🏾👉🏾👉🏾 Check off each completed feature below.

- [X] A subset of pages require the user to log in before accessing the content
  - [ ] Users can log in and log out via GitHub OAuth with Passport.js
  - [X] ***We have implemented a system with file-permissions where a user needs to both be logged in, and also have the permission to view that text if the text is shared***
- [ ] Restrict available user options dynamically, such as restricting available purchases based on a user's currency
- [ ] Show a spinner while a page or page element is loading
- [ ] Disable	 buttons and inputs during the form submission process
- [ ] Disable buttons after they have been clicked
- [ ] Users can upload images to the app and have them be stored on a cloud service
- [ ] 🍞 [Toast messages](https://www.patternfly.org/v3/pattern-library/communication/toast-notifications/index.html) deliver simple feedback in response to user events

## Final Demo GIF

🔗 [Here's a GIF walkthrough of the final project](👉🏾👉🏾👉🏾 your link here)

## Reflection

### 1. What went well during this unit?

I think we have finished the main parts of the projects pretty strongly. Obviously, there are a lot of parts that can be improved and a lot of stretch features that can be implemented, but overall, I am satisfied with product. It gave us a lot of experience on building structures of friends, notifications, filesharing, permissions and dynamic annotations with merged data. I believe we will have a nice grade.

### 2. What were some challenges your group faced in this unit?

The main challenge was collaboration. Apart from force pushing and other things, there were a lot of struggle for integrating parts done by different people. We also pivoted away from the earlier design a lot and followed where the code took us in terms of visuals.

### 3. What were some of the highlights or achievements that you are most proud of in this project?

I think our annotation feature is top tier! We solve the overlap problem by merging different threads of annotations. We carry the annotation with the most karma (upvotes-downvotes) to the top. We also have a filesharing system which at times, felt like I was building Google Drive hahaha!

### 4. Reflecting on your web development journey so far, how have you grown since the beginning of the course?

I think the parts that I grew the most were database design, and overall API logic. Especially during the development of the annotation merge, and understanding if the user highlighted a text or not, it was quite hard to implement a system to track overlaps and also merge them in the database as well. Other than that, in general, I think I have a much more systematic understanding of how to develop a web application since I know that a reset database script is good practice, how to build readable APIs, how to structure directories and what are best practices!

### 5. Looking ahead, what are your goals related to web development, and what steps do you plan to take to achieve them?

The main goal is to push quality products for an impressive portfolio. It should provide us with enough expertise and skills to show to recruiters. We also want to land a good internship or have a nice work experience to also learn working in large projects.
