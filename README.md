![App Screenshot](https://raw.githubusercontent.com/meysam-gheitasi/pure-js-app/main/images/pure-js-app-hero.png)

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)


# Pure JavaScript website 



![فارس](https://user-images.githubusercontent.com/125398461/234186932-52f1fa82-52c6-417f-8b37-08fe9250a55f.png)
[فارسی](https://github.com/meysam-gheitasi/purejs-app/blob/main/README-fa.md)
### []()

In this project, almost all the necessary skills to master JavaScript have been implemented in the form of a store with an admin panel.


## 📋 Table of Contents

1. 🤖 [Introduction](#-introduction)
2. ⚙️ [Tech Stack](#%EF%B8%8F-tech-stack)
3. 🔋 [Features](#-features)
4. 🤸 [Demo And Quick Start](#-Demo-And-Quick-Start)
5. 🚀 [More](#-more)
## 🤖 Introduction

This project consists of 3 parts: a page for admin to create and edit limited products as well as display them sorted.
For each product by product ID, a dedicated page is created to edit the product information with the possibility of displaying the last time the product was edited and finally a page to display all the products in the store with the possibility of adding to the shopping cart and the possibility of managing the selected products in the shopping cart. For users.
## ⚙️ Tech Stack

1. JavaScript.
2. CSS and local variables.
3. Columns in Bootstrap.
4. Using the moment package as a CDN file to have the date of creation and    
    editing of the products.
5. Using the jalali-moment package as a CDN file to have a snapshot date.
6. Using the uuid.js package as a CDN file to register the product ID.
7. Use of fonts in the project.
## 🔋 Features

👉 On the admin page:

1. Product manufacturing with unique ID features and manufacturing date.
2. Displaying products created by elements created with JS.
3. sort the products created in two modes, the time of creation and the
       time of editing the products.
4. Search letter by letter among product names.
5. Existence of delete button, announcement of availability for each
       product.
6. Save all changes in the local storage of the user's browser.
7. Linking the name of each product to its own page using ID.

👉 On the dedicated product editing page:

1. Displaying product information by taking the product ID from the URL of
       the created page or redirecting the user to the admin page if there is
       an invalid URL.
2. Displaying product information in pre-created elements in the HTML file.
3. Ability to edit and save all product information in real-time without
       pressing the save information button.
4. Real-time display of the last time the product was edited.

👉 On the store page:

1. Receiving products from local storage and displaying all products that 
      are announced as available along with the default photo. In two display
      modes: browser mode in 2 columns and mobile mode in 1 column.
2. Static elements and dynamic data of product display, such as reactive 
       components, are added to a created element dev in the form of inner 
       HTML, and finally, they are added to a print element in the HTML file.
3. By selecting each product, it will be added to the shopping cart. And 
       by choosing several times from each product, only the feature of the 
       number of that product in the shopping cart will increase.
4. Display the number of products in the shopping cart on the shopping 
       cart icon on the store page.
5. Shopping cart information is stored in local storage.
6. By clicking on the shopping cart icon, it is possible to display and 
       edit the number and delete individual or all products in the cart.
   
## 🤸Demo And Quick Start

Running the website online

### [www.pure-js-app.html](https://meysam-gheitasi.github.io/pure-js-app/)


Cloning the Repository

```bash
  git clone https://github.com/meysam-gheitasi/purejs-app.git
  cd purejs-app
```


## 🚀 More

Coming Soon...
