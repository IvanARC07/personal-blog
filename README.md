# 📝 Personal Blog Site

## 📌 Description
This project showcase a classic web development style. The project will start static for the most part, and increment gradually until it becomes a fully functional web application. Feature enhancements will include: 

* User authentication
* SQL based data storage
* Scalable front-end and back-end implementations

## 🧠 Design Patterns

### 📂 File Architecture
```bash
├── src/
│    ├── assets/          # public access (logo, svgs, etc)
│    ├── js/              
│    │  └── utils/        # utilities functions and helpers
│    ├── pages/
│    │  └── blogs/
│    │    └──blogs.js     # blog specific logics
│    ├── styles/
│    │  └── styles.css    # for global styles
│    └── main.js          # main javascript entrypoint
├── public/               # static files (sitemaps, favicon, etc)
└── index.html            # main HTML file
```
### 🧩 Technologies
HTML5 semantic tags for layout and inner children (header, main, footer, address, caption, etc).
  ```html
  <header></header>
  <main></main>
  <footer></footer>
  ```
CSS modules for more maintainable styles, and nesting for precision and separation of conserns
  ```css
    ul{
      li{
        a{
          color: blue
        }
      }
    }
  ```

Javascript modules
  ```js
  import {component} from 'component'
  export const component = () => {...}
  export default {component}
  ```

## 🛣️ Roadmap

- [] Static layout using semantic HTML
- [] Add responsive styles
- [] Implement SQL
- [] User authentication and authorization
- [] Admin panel for content creation

## 💡 Future ideas
- Dark mode toggle
- Maybe comment system
- Markdown support for blogs
- tag category and filtering

## 🪪 License
MIT Licensed