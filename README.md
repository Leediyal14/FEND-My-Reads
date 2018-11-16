## My Reads Project

   Project 6 for **Google - Udacity FEND Nanodegree Scholarship** Program.

#### Project Overview

   * This project shows a **Bookshelf App** that allows you to select and categorize books you have read, are currently reading, or want to read. 

   * The project emphasizes using **React** to build the application and provides an API server and client library that will use to persist information as the user interact with the application.

#### How to run this App?

   * Clone or download this repository to your local computer. If downloaded, unzip the folder.

   * At terminal, check that if you have Node.js installed. If installed, then move to the new cloned directory by using `cd` command.

   * From inside that new directory, run the following command to install all dependencies
                    `npm install`

    and after that start the server with the following:
                    `npm start`

   * The My Reads App will automatically open in the    browser. You can run manually from [click here](http://localhost:3000/) too.

#### App Functionality

   * In this app, there are two pages. The **Main Page** displays a list of **shelves** (i.e. categories), each of which contains a number of books. The three shelves are:

                    * Currently Reading
                    * Want to Read
                    * Read

   * Each book has a control that lets you select the shelf for that book. When you select a different shelf, the book moves there. The default value for the control is always the current shelf the book is in.

   * The **Search Page** has a text input that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets you add the book to your library.

   * When a book is on a bookshelf, it has the same state on both the main application page and the search page.

   * The search page also has a link to **/** (the root URL), which leads back to the main page.

#### Notes

   * The starter project provided by Udacity has some HTML, CSS, JS files and images to start this project.

   * For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

    **Thank You**