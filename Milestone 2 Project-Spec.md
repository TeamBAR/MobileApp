# **Book Finder**

## Table of Contents

1. [App Overview](#App-Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
1. [Build Notes](#Build-Notes)

## App Overview

### Description 

**A discovery app for book lovers, allowing users to search for books by title, author, or genre, and manage their personal reading list.**

### App Evaluation

<!-- Evaluation of your app across the following attributes -->

- **Category:** Education / Literature
- **Mobile:** Mobile is essential for providing instant access to book details, whether at a bookstore, library, or on the go.
- **Story:** Helps book lovers find and keep track of their next read easily. Be it for reading pleasure or for researching over a certain topic, this application is your companion in all matters books.
- **Market:** Students, researchers, and casual readers.
- **Habit:**  Users frequently use the app to discover new books, manage their reading list, or explore recommendations.
- **Scope:**
    - V1: Search functionality with basic details (title, author, description).
    - V2: Integrate with Google Books for more comprehensive data and user reviews.
    - V3: Add reading list management and personalized recommendations.
## Product Spec

### 1. User Features (Required and Optional)

Required Features:

- [X] **Search for books by title, author, or genre.**
- [X] **Display book details, including title, author, description, and cover image.**
- [X] **Save books to a personal "Reading List" for tracking.**

Stretch Features:

- [X] Have the option to view the abstract if available.
- [X] Link certain books based on selections or prefrences to recommend other options.

### 2. Chosen API(s)

- **Google Books API:**
  - **Feature: Fetch book details, including title, author, description, cover image, and user reviews.**
- Link to Google API documentation.
--https://developers.google.com/books/docs/overview

### 3. User Interaction

Required Feature

- **User enters a title, author, or genre into the search bar**
  - => **The app fetches matching books from the Google Books API and displays them in a list.**

- **User taps on a book from the search results.**
  - => **The app displays the book’s details, including its title, author, description, and cover image.**


## Wireframes

<!-- Add picture of your hand sketched wireframes in this section -->
![BookFinderWireframe](https://hackmd.io/_uploads/B1CTUJnGke.png)
![Android Compact - 1](https://hackmd.io/_uploads/BJjssbFX1e.png)
![Android Compact - 3](https://hackmd.io/_uploads/HkjsiZFmJe.png)
![Android Compact - 4](https://hackmd.io/_uploads/rJjiiWYX1x.png)



### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Build Notes

Here's a place for any other notes on the app, it's creation 
process, or what you learned this unit!  

For Milestone 2, include **2+ Videos/GIFs** of the build process here!

![](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHI4NWF6MjhtbHZ3czJiaXRzZXNzbWo1Z3F1dzBtaHZwdGpwOW9hdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/32MqRiDS0nPJUkr3Ns/giphy.gif) ![](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExMjdiZ2h3MjRpMzBmYmZuNjV5Z2FqdWFra3Uxczd2amlqdjg0NnVyciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZJiPjzfiynbsLLt0Hk/giphy.gif) 

## License

Copyright **2024** **BARTeam**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
