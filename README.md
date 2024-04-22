# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/ababaug/blog-preview-card-main]
- Live Site URL: [https://ababaug.github.io/blog-preview-card-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<body>
  <div class="container">
    <header>
      <div class="article-img">
        <img src="./assets/images/illustration-article.svg" alt="" />
      </div>
    </header>
    <main class="article-content">
      <span class="article-nav">Learning</span>
      <p class="article-pub">Published 21 Dec 2023</p>
      <h1>HTML & CSS foundations</h1>
      <p class="article-paragraph">
        These languages are the backbone of every website, defining structure,
        content, and presentation.
      </p>
    </main>
    <footer class="article-footer">
      <img src="./assets/images/image-avatar.webp" alt="" />
      <p>Greg Hooper</p>
    </footer>
  </div>
</body>
```

```css
@font-face {
  font-family: Figtree-italic;
  src: url(assets/fonts/Figtree-Italic-VariableFont_wght.ttf);
}

@font-face {
  font-family: Figtree;
  src: url(assets/fonts/Figtree-VariableFont_wght.ttf);
}

@font-face {
  font-family: Figtree-Extra;
  src: url(assets/fonts/static/Figtree-ExtraBold.ttf);
}

@font-face {
  font-family: Figtree-semi;
  src: url(assets/fonts/static/Figtree-SemiBold.ttf);
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 812px;
  background-color: yellow;
}

.container {
  background-color: white;
  width: 327px;
  height: 501px;
  border-radius: 20px;
  box-shadow: 8px 8px black;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
}

.article-img {
  width: 279px;
  height: 200px;
}

.article-img img {
  width: 100%;
  height: 100%;
  border-radius: 10px;
  object-fit: cover;
}

.article-content {
  width: 279px;
  height: 173px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.article-content .article-nav {
  background-color: yellow;
  border: 0;
  padding: 8px 12px;
  border-radius: 4px;
  font-family: Figtree-extra;
  font-size: 12px;
  width: 73px;
}

.article-content .article-pub {
  font-family: Figtree;
  font-size: 12px;
}

.article-content h1 {
  font-family: Figtree-extra;
  font-size: 20px;
  line-height: 150%;
}

.article-content .article-paragraph {
  font-family: Figtree-semi;
  font-size: 14px;
  line-height: 150%;
  color: grey;
}

.article-footer {
  display: flex;
  gap: 12px;
  align-items: center;
  align-self: flex-start;
  padding: 0 24px;
}

.article-footer img {
  width: 32px;
  height: 32px;
}

.article-footer p {
  font-family: Figtree-extra;
}

@media only screen and (min-width: 600px) {
  .container {
    width: 384px;
    height: 522px;
  }

  .container:hover {
    box-shadow: 14px 14px black;
  }

  .article-img {
    width: 336px;
  }

  .article-content {
    width: 336px;
    height: 194px;
  }

  .article-content .article-nav {
    font-size: 14px;
    width: 82px;
  }

  .article-content .article-pub {
    font-size: 14px;
  }

  .article-content h1 {
    font-size: 25px;
    line-height: 150%;
  }

  .article-content h1:hover {
    color: yellow;
    cursor: pointer;
  }

  .article-content .article-paragraph {
    font-size: 16px;
    line-height: 150%;
  }
}
```

## Author

- Website - [https://www.linkedin.com/in/augustine-stephen-abah-51103090/]
- Frontend Mentor - [@ababaug](https://www.frontendmentor.io/profile/ababaug)
