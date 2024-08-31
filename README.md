# Frontend Mentor | Social Links Profile Solution

## Overview

This project is a simple profile card that displays social media links as buttons. The design is clean and focused, offering quick access to different social media platforms through easily identifiable buttons.

## What I Learned

### CSS Flexibility

In this project, I learned that there are numerous tools and techniques in CSS to achieve the same visual outcome. Whether it's using flexbox, grid, or simply adjusting margins and paddings, CSS offers various approaches to solve design challenges.

### Consistency and Practice

The more I work on these projects, the easier it becomes to bring a design to life. Consistent practice and staying hands-on with the material has significantly improved my ability to translate designs into code.

### Fonts and Pseudo-Classes

I explored different ways to incorporate fonts into a project, making the typography more appealing. Additionally, I experimented with various pseudo-classes, learning how they can be effectively used to enhance user interaction and style elements conditionally.

## Technologies Used
-- **HTML5**: For structuring the content semantically.
-- **CSS3**: For styling the profile card, including button design, font integration, and hover effects.

### HTML Structure
```html
<div class="all-content">
    <img class="jess-flic" src="./assets/images/avatar-jessica.jpeg" alt="jessica name">
    <h5 class="name">Jessica Randall</h5>
    <h6 class="location">London, United Kingdom</h6>
    <p>"Front-end developer and avid reader."</p>

    <a class="btn" href="https://github.com" target="_blank">GitHub</a>
    <a class="btn" href="https://www.frontendmentor.io" target="_blank">Frontend Mentor</a>
    <a class="btn" href="https://www.linkedin.com" target="_blank">LinkedIn</a>
    <a class="btn" href="https://twitter.com" target="_blank">Twitter</a>
    <a class="btn" href="https://instagram.com" target="_blank">Instagram</a>
</div>
```

### CSS for Button Styling
```css
.btn {
    display: block;
    width: 100%;
    text-align: center;
    padding: 10px;
    margin: 10px 0;
    background-color: #333;
    color: #fff;
    text-decoration: none; /* Removes the underline */
    border-radius: 5px;
    font-family: 'Arial', sans-serif;
    font-size: 1rem;
}

.btn:hover {
    background-color: #555;
}
```

## Final Thoughts

This project was a great opportunity to reinforce my understanding of CSS and its flexibility. I also realized the importance of consistency in practice, as it makes the process of bringing a design to life much smoother. The tools and techniques I’ve learned here, particularly around fonts and pseudo-classes, will certainly be useful in future projects.
