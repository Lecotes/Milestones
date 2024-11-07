# Lecotes

CodePath WEB103 Final Project

Designed and developed by: Enes Akyuz, Dorisa Shehi, Steven Yang

🔗 Link to deployed app:

## About

### Description and Purpose

Lecote will be a web application that allows professors, writers or creators to post literary works, and text that allow specific people or public to write highlighted commentaries as interpretations and notes that they can upvote or downvote. The web application aims to build the perfect collective note-taking environment via community feedback and evaluation. It can also serve as a community resource for lecture transcriptions, writings, literary works or anything that needs interpretations, commentaries or critique. Students can use these notebooks as a point of reference and better understand their lectures, textbooks or literary works.

### Inspiration

The main inspiration came from the lyrics website "[Genius](https://genius.com/Lady-gaga-and-bruno-mars-die-with-a-smile-lyrics)" where song lyrics can be interpreted by the users of the website, and the top rated interpretation is shown as the official one. We are thinking of carrying this application and extending it for academic, and literary purposes so that we can enhance students' understanding via students' collaboration and note-taking themselves using different perspectives from the students.

## Tech Stack

Frontend: React, Tailwind, Sass, HTML-CSS-Js

Backend: Express.js, Node.js, Railway (for ORM and PostgreSQL), Passport.js, We can also use Supabase for ORM

## Features

**Main Features**

1. ✅  **User registration:**
![Signuo](https://github.com/user-attachments/assets/b0c619fb-51ee-499e-a027-241cce93127e)

   1. Users can create accounts using their emails and passwords.
2. **Profile creation:**

   1. Users can add their names, age, or affiliation (university, company, research group etc), location.
3. **Search functionality:**

   1. Users can search and add other users as friends.
4. **Group formation:**

   1. Users can form annotation groups.
   2. The user can restrict who can participate in a group or assign work to individual users.
5. **Upload Material:**

   1. Users can upload text, pdfs, or docs and see what they have uploaded.
   2. Users can also directly write text in the website.
6. **Adjust Visibility:**

   1. The user can restrict who, or which group, can annotate this work.
      1. The user should be able to assign readers, commenters and contributors.
   2. When uploading material, the upload screen should have a public/restricted switch.
      1. If public, the material can be seen and commented by anyone registered on the website.
      2. If restricted, only the restricted groups can see the material.
7. ✅ **Annotate Material**
![Annotation](https://github.com/user-attachments/assets/c3587a8e-408f-45d0-a0eb-11b0836943f4)

   1. Users can highlights a certain part of the material.
   2. Users can write their annotation/note/interpretation for the higlighted section.
8. **Upvote Downvote**

   1. Users can upvote or downvote the annotations/comments/contributions they see.
   2. The top voted ones stays up as the main notes for the work which are shown at the top.
9. **Approvals and Deletions**

   1. If users submit to my restricted uploaded work, I can choose to "not approve" or "delete" the commentary.
   2. I can choose to have only the "approved" comments visible.
10. **Reporting**

    1. The users can report any inappropriate uploaded work or commentary.

## Installation Instructions

[instructions go here]
