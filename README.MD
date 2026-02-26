# To-Do App using Python and Flask

## Description
A simple to-do app built with Python using the Flask framework. The app allows users to create, edit, and manage their tasks. It is designed to showcase my skills in web development using Flask, data handling, and cloud deployment using AWS.

Current functionality only allows users to edit tasks in a single master to-do list. For future improvements, I'd consider creating functionality to manage different to-do lists (like a traditional Reminders app) and viewing completed tasks.  

![Current Version of the App](images/current-version-of-romans-to-do-app.png)

---

## Table of Contents
- [Usage](#usage)
- [Features](#features)
- [Future Improvements](#future-improvements)
- [Technologies Used](#technologies-used)
- [Challenges Faced](#challenges-faced)
- [AWS Deployment](#aws-deployment)
- [Contact Information](#contact-information)
- [Acknowledgments](#acknowledgments)
- [Links](#links)

---

## Usage
1. Run the app: `python main.py`
2. Open a web browser and go to `http://127.0.0.1:5000`
3. Interact with the app to create, edit, and manage your tasks.

---

## Features
- Create tasks with descriptions and due dates.
- Edit existing task's description and due dates.
- Mark tasks as completed (which will also remove them from your lists).

---

## Future Improvements
After I tackle a few other projects, I'd consider enhancing the app in the future, including:
- Give user ability to sort to-dos by name, due status, or due date.
- Give user ability to create different lists with to-do tasks.
- Give user ability to move tasks between lists.
- Allow user to view completed tasks within each list.
- Allow user to edit and delete lists. 
- Update the homepage to display all to-do lists and when user clicks on a list, it will take them to a unique URL with that to-do list.
- Adding user authentication for personalized task management.
- Implementing task categorization and filtering.

---

## Technologies Used
- Python
- Flask
- Pandas
- HTML
- Bootstrap (CSS Framework)
- AWS (Cloud Deployment)

---

## Challenges Faced
One of the biggest challenges of creating this app was writing HTML and CSS code. I'm also not very familiar with Bootstrap framework, so it took a lot of experimenting and debugging to get the app going. 

For example, I initially used HTML tables to display the list of tasks, but I couldn't get it to display the way I wanted. I found a work-around by using containers and divs. Here's what an earlier draft looked like: 

![Earlier Version of the App](images/first-version-of-my-to-do-app.png)

---

## AWS Deployment
The app is deployed on AWS cloud services. Below is the architecture diagram of the deployment:

![AWS Architecture](images/aws-architecture.png)

---

## Contact Information
I welcome any feedback from the community and you're welcome to fork the repository for your own project.  
You can reach me at [roman.pk@yahoo.com](mailto:roman.pk@yahoo.com).

---

## Acknowledgments
- [Bootstrap](https://getbootstrap.com) - CSS framework for styling.
- [Pandas](https://pandas.pydata.org) - Used for data manipulation.

---

## Links
- Live Demo - Deployed on AWS  
- [GitHub Repository](https://github.com/Kuldeepacharya11/todohawa)