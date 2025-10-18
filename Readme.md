Lab 4: Advanced HTML & CSS

This repository contains the completed exercises for the Lab 4 assignment in the Web Application Development course. The lab focuses on modern web development techniques, including website deployment, advanced form creation with Bootstrap, and responsive layouts using CSS Flexbox.

Course: Web Application Development

Student: Lê Hoàng Khanh (ITCSIU23013)

Instructors: Assoc. Prof. Nguyen Van Sinh, MSc. Nguyen Trung Nghia

Live Demo

The personal CV from Exercise 1 has been deployed using GitHub Pages and is available at the following URL:

https://khanh-per.github.io/Lab2_WebDemo/

Exercises Summary

This repository includes the solutions for the following three exercises:

1. Exercise 1: GitHub Pages Deployment (15 points)

Objective: To deploy a personal static website to a live URL (https://khanh-per.github.io/Lab2_WebDemo/).

Outcome: A personal CV page was successfully published using GitHub Pages, including repository setup, file upload, and correct configuration.
![alt text](CV.png)

2. Exercise 2: Advanced Form Creation (30 points + 5 Bonus)

Objective: To build a detailed survey form based on a provided design, utilizing various input types.

Outcome: The form was created using semantic HTML and styled with Bootstrap 5, incorporating responsive grid layouts and standard form components to meet the bonus requirements.
![alt text](SurveyForm.png)

3. Exercise 3: 3-Column Flexbox Layout (20 points)

Objective: To implement a fixed-width, 3-column layout (Sidebar, Main Content, Sidebar) using CSS Flexbox.

Outcome: A webpage with a full-width header and footer was created. The central content area was structured using a Flexbox container to manage the proportions and arrangement of the three columns.

Explain the code:
    <div class="container">: the main wrapper in the entire layout, it act like the primary parent for the header, middle-content and footer

    display: flex; this turn the .container into a flexbox container

    flex-direction: column; this is the key point. This is how I get the header on top, the .middle-section in the middle, and the footer at the bottom.

Technologies Used

HTML5

CSS3 (Flexbox)

Bootstrap 5

GitHub & GitHub Pages

Exercise 4 

Objective: : Implement following pages using CSS, HTLM and applying Flexbox to layout the pages 

OutCome: The code produces a complete and professional-looking single webpage that visually matches the "San Joaquin Valley Town Hall" image you provided.

Explain the code:
    <div class="main-layout">: This is the most important structural element. It's a wrapper around the main content and the sidebar, and we will turn this div into a Flexbox container.

    <main> and <aside>: These semantic tags clearly separate the primary content from the secondary sidebar content.