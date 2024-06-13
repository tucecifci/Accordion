# Accordion

Hello everybody! 👋 </br>
✨ Welcome to the Accordion Project! This project is a simple and interactive accordion component built using HTML, CSS, and JavaScript. It allows users to expand and collapse sections of content, providing a clean and organized way to display information.


## 👀 Overview

### 📷 Screenshot

![screencapture-tucecifci-github-io-Accordion-2024-06-13-11_26_35](https://github.com/tucecifci/Accordion/assets/151346784/a66706ff-0ee8-4108-b1ac-f578006c6d74)
![screencapture-tucecifci-github-io-Accordion-2024-06-13-11_27_03](https://github.com/tucecifci/Accordion/assets/151346784/b7063a83-9217-485b-b19e-e82c29ade9db)

![screencapture-tucecifci-github-io-Accordion-2024-06-13-11_26_52](https://github.com/tucecifci/Accordion/assets/151346784/4ed4b7a7-65d2-40ba-97d3-bf21a6e099ab)


### 🔗 Links

- [https://tucecifci.github.io/Random-Quotes/](https://tucecifci.github.io/Accordion/)

## My process

### 💡 Built with

- HTML: For the structure of the accordion.
- CSS: For styling and animations.
- JavaScript: For adding interactivity to the accordion.

  
### 🧠 What I learned

While working on the Accordion project, I learned:

- Event Handling: How to use JavaScript to add click event listeners to elements.
- DOM Manipulation: How to dynamically change the class of an element to show or hide content.
- CSS Transitions: How to use CSS to create smooth animations for expanding and collapsing sections.
- Responsive Design: Improved skills in making web components responsive across different devices.

```javascript
const accordion = document.getElementsByClassName("content-container");
for (i = 0; i < accordion.length; i++) {
  accordion[i].addEventListener("click", function () {
    this.classList.toggle("active");
  });
}
```

### 👩🏼‍💻 Features

- Texpandable Sections: Click on a section header to expand or collapse the content.
- Smooth Animations: CSS transitions for a smooth opening and closing effect.
- Responsive Design: The accordion is fully responsive and works well on various screen sizes.

### 🤔 How to Use

- Expanding a Section: Click on any section header to expand the content.
- Collapsing a Section: Click again on the expanded section header to collapse it.


### 🤌🏻 Useful resources

- [https://www.goodreads.com/quotes](https://www.youtube.com/watch?v=5fb2aPlgoys)

## 🏳️‍🌈 Author

- Tuğçe Çifci - [@tucecifci](https://github.com/tucecifci)
- Frontend Mentor - [@tucecifci](https://www.frontendmentor.io/profile/tucecifci)
