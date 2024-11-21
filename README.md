# Lecotes

CodePath WEB103 Final Project

Designed and developed by: Enes Akyuz, Dorisa Shehi, Steven Yang

🔗 Link to Project Repository: [Lecotes Codebase](https://github.com/Lecotes/Codebase)

🔗 Link to deployed app: [https://lecotes.onrender.com/](https://lecotes.onrender.com/)

## About

### Description and Purpose

Lecote will be a web application that allows professors, writers or creators to post literary works, and text that allow specific people or public to write highlighted commentaries as interpretations and notes that they can upvote or downvote. The web application aims to build the perfect collective note-taking environment via community feedback and evaluation. It can also serve as a community resource for lecture transcriptions, writings, literary works or anything that needs interpretations, commentaries or critique. Students can use these notebooks as a point of reference and better understand their lectures, textbooks or literary works.

### Inspiration

The main inspiration came from the lyrics website "[Genius](https://genius.com/Lady-gaga-and-bruno-mars-die-with-a-smile-lyrics)" where song lyrics can be interpreted by the users of the website, and the top rated interpretation is shown as the official one. We are thinking of carrying this application and extending it for academic, and literary purposes so that we can enhance students' understanding via students' collaboration and note-taking themselves using different perspectives from the students.

## Tech Stack

Frontend: React, Tailwind, Sass, HTML-CSS-Js

Backend: Express.js, Node.js, Railway (for ORM and PostgreSQL), Passport.js

## Features

**Main Features**

1. **Signup**

Users can create an account on the application.

2. **Login**

Users can login to the application with a previously created account.

3. **Add Text**

Users can upload their texts.

4. **Add Friends**

Users can add friends and view their friends list.

5. **Share Text**

Users can share texts with other people to annotate during file creation.

6. **Add/delete/edit Annotation**

Users can add/delete/edit annotations to the text by highlighting a section and adding their annotations.

7. **Merge Annotation**

Annotations are automatically merged if there are overlapping annotations.

8. **Add/delete/edit Replies**

Users that have access to the text can reply to annotations, and delete/edit them afterwards.

9. **Upvote Downvote System**

Users can upvote or downvote an annotation, each unique to only once per reply/annotation. The annotation with the most karma stays on top.

10. **Search Features**

Users can search files or friends (friends can be searched both during the share file or friendslist).

## Installation Instructions

A deployed version is in this link: [Lecotes Codebase](https://github.com/Lecotes/Codebase)

For seperate versions that run on Render, please visit: [Express backend](), [React frontend](https://github.com/Lecotes/frontend_deploy)

To run the code, you need to change the addresses in the url's since these are deployed versions. An environment variable is recommended for the API calls. Also, have a Railway database key, in which, resetDatabase.js in the backend can create tables. Other than these `npm install` and `npm start` for both `backend` and `frontend` directories should do the trick!
