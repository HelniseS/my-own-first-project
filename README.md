# Helnise Portfolio Website 🌐

Welcome to my personal portfolio website!This site was created to present my journey as a web developer and IT support specialist, showcasing my technical skills, education, and professional interests. It serves as a digital résumé and an online space where recruiters, collaborators, or anyone interested in my work can learn more about me. 
## 🚀 Live Preview

 https://helnises.github.io/my-own-first-project/

---
[Contents](#contents)
  * [User Goals](#user-goals)
  * [User Stories](#user-stories)
  * [Website Goals and Objectives](#website-goals-and-objectives)
  * [Wireframes](#wireframes)
  * [Design Choices](#design-choices)
    + [Typography](#typography)
    + [Colour Scheme](#colour-scheme)
    + [Images](#images)
    + [Responsiveness](#responsiveness)
- [Features](#features)
  * [Existing Features](#existing-features)
    + [Header](#header)
      - [Instructions](#instructions)
      - [Feedback](#feedback)
    + [Landing View](#landing-view)
    + [Question View](#question-view)
    + [Final Score View](#final-score-view)
    + [Footer](#footer)
       * [Future Enhancements](#future-enhancements)
- [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Libraries & Framework](#libraries---framework)
  * [Tools](#tools)
- [Testing](#testing)
  * [Bugs Fixed](#bugs-fixed)
  * [Responsiveness Tests](#responsiveness-tests)
  * [Code Validation](#code-validation)
    + [HTML](#html)
    + [CSS](#css)
  * [User Story Testing](#user-story-testing)
  * [Feature Testing](#feature-testing)
  * [Accessibility Testing](#accessibility-testing)
  * [Lighthouse Testing](#lighthouse-testing)
  * [Browser Testing](#browser-testing)
- [Deployment](#deployment)
  * [To deploy the project](#to-deploy-the-project)
  * [To fork the project](#to-fork-the-project)
  * [To clone the project](#to-clone-the-project)
- [Credits](#credits)
## 📂 Project Structure

```bash
├── index.html         # Main HTML file
├── style.css          # Custom CSS styling
├── assets/            # Folder for images, icons, etc.
         
```

---

## Features

- Responsive design
- Smooth navigation bar
- Professional photo and branding
- Skills, education, and experience sections
- Services offered
- Contact form with email & phone details
- Downloadable CV button

---

## User Goals

This portfolio website has been carefully crafted with the user in mind. Key user experience considerations include:
* User friendly navigation.
* Non distracting background.
* Learn about me.
* Explore my skills.
* Review my education.
* Connect with me.
* Get a snapshot of my work style.

---
## User Stories

This portfolio project evolved through several stages of learning and iteration:

* As a visitor, I want to quickly understand who the developer is and what they do,
So that I can decide if I’m interested in exploring their work or contacting them.

* As a hiring manager, I want to view the developer’s education and technical skills in a clear, professional format,
So that I can evaluate their suitability for a job role.

* As another developer, I want to see what tools and technologies they use,
So I can learn from their tech stack or potentially collaborate.

*  As a trainer or mentor, I want to assess the developer’s progress and areas of expertise,
So that I can give relevant feedback or advice.

* As a recruiter with limited time, I want to scan the portfolio and find education, skills, and contact info easily,
So that I can make a quick hiring decision or shortlist the developer.

## Website Goals and Objectives

* Showcase my skills and experience.
* Create a professional online presence. 
* Highlight my education and training.
* Offer simple and accessible ways to get in touch with me.
* Use responsive, mobile-first design to ensure compatibility across all devices.
* Organize content into logical sections for easy finding. 
* Increase overall website traffic by increasing rankings on search engine.



 ## Target Audience

* Hiring Managers and Recruiters
* Fellow Developers
* General Viewers
* Students and Educators

[Back to top](#contents)
## Wireframes

Wireframes were designed using Balsamiq tool. Following best practices, mobile version was designed first, then tablet and lastly the laptop view. There are some deviations from wireframes in the live version of the quiz. It is one page website to enhance the logical flow. I have added level user selected in the question view, a number of correct and wrong answers as well. A functionality of local storage to display top 5 results is included in the final version as well. 

 [Mobile Wireframes](assets/images/mobile.wireframe.pdf)

 [Tablet Wireframes](assets/images/tablet.wireframe.pdf)

 [Desktop Wireframes](assets/images/Computer.wireframe.pdf)

 [Back to top](#contents)

 ## Design Choices

### Typography

| Purpose             | Font Family         | Weight     | Style         |
|---------------------|---------------------|------------|---------------|
| Primary Font        | `Poppins`, sans-serif | 400–700   | Clean, modern |
| Headings (`h1`, `h2`) | `Poppins`, sans-serif | 600–700 | Bold, prominent |
| Body Text (`p`)     | `Poppins`, sans-serif | 400        | Readable, light |
| Navigation / Buttons | `Poppins`, sans-serif | 500–600   | Clear, accessible |

**Fallback Fonts:** `sans-serif`  
**Font Source:** Google Fonts – [Poppins](https://fonts.google.com/specimen/Poppins)


### Colour Scheme

| Color Name            | Hex Code   | Usage                               | Preview                          |
|-----------------------|------------|-------------------------------------|----------------------------------|
| Background            | `#fdf6e3`  | Page background                     | ![#fdf6e3](https://via.placeholder.com/20/fdf6e3?text=+) |
| Primary Text          | `#333333`  | Headings, main body text           | ![#333333](https://via.placeholder.com/20/333333?text=+) |
| Accent - Pink         | `#ff69b4`  | Buttons, highlights                 | ![#ff69b4](https://via.placeholder.com/20/ff69b4?text=+) |
| Accent - Light Pink   | `#ffb6c1`  | Hover effects, borders              | ![#ffb6c1](https://via.placeholder.com/20/ffb6c1?text=+) |
| Navbar - Plum         | `#dda0dd`  | Navigation bar background           | ![#dda0dd](https://via.placeholder.com/20/dda0dd?text=+) |
| Button - Teal         | `#a2d8d3`  | Button backgrounds, cards           | ![#a2d8d3](https://via.placeholder.com/20/a2d8d3?text=+) |
| Button - Hover        | `#f7b7b7`  | Hover state on interactive elements | ![#f7b7b7](https://via.placeholder.com/20/f7b7b7?text=+) |
| Subtle Text           | `#555555`  | Footer, secondary information       | ![#555555](https://via.placeholder.com/20/555555?text=+) |
| Light Gray (Border)   | `#e3e3e3`  | Border lines, section dividers      | ![#e3e3e3](https://via.placeholder.com/20/e3e3e3?text=+) |

> This palette ensures a soft, inviting interface with enough contrast for readability and accessibility.






![Contrast Grid](docs/contrast-grid-color.pn

## 🛠️ Built With

- HTML5
- CSS3
- GitHub for version control

---
🧭 Wireframe

The initial layout and structure of the portfolio were planned using wireframes to ensure a clean, user-friendly interface. These wireframes helped guide the placement of navigation, service cards, skill highlights, and the contact form.

[Computer.wireframe.pdf](https://github.com/user-attachments/files/20410421/Computer.wireframe.pdf)
[Ipad wireframe.pdf](https://github.com/user-attachments/files/20410428/Ipad.wireframe.pdf)
[Iphone wireframe.pdf](https://github.com/user-attachments/files/20410441/Iphone.wireframe.pdf)

## 🧠 What I Learned

- Structuring a responsive portfolio from scratch
- Using semantic HTML for accessibility
- Enhancing user experience with clean layout and forms
- CSS techniques for card layouts, navigation bars, and form design

---

## 📬 Contact

If you'd like to collaborate or get in touch:

- Email: [helnise-santos12@hotmail.com]
- Tel: [ +777 846 8127 ]

---

## 📄 License

This project is open for learning and sharing purposes. Please credit the original author if reused or modified.
