# HTML5 Interview Questions &amp; Answers 2024

Question: **What is the purpose of the `<!DOCTYPE html>` declaration?**

> Answer: `<!DOCTYPE html>` is an instruction to the web browser about what version of HTML the page is written in. In HTML5, <!DOCTYPE html> is used to specify that the document is HTML5.

Question: What is the difference between localStorage and sessionStorage objects?

> Answer: Both localStorage and sessionStorage are part of the web storage API and are used to store data on the client side. The main difference is that localStorage has no expiration time, while sessionStorage gets cleared when the page session ends (i.e., when the page is closed).

Question: What is the use of the canvas element in HTML5?

> Answer: The canvas element is used to draw graphics on a web page that are on the fly via scripting (usually JavaScript). It can be used to draw graphs, make photo compositions, create animations, or even do real-time video processing or rendering.

Question: What are data- attributes good for in HTML?

> Answer: HTML5 introduced custom data attributes. They are used to store custom data private to the page or application. The stored data can then be used in the JavaScript to create a more interactive user experience.

Question: What is the difference between SVG and Canvas?

> Answer: SVG is a language for describing 2D graphics in XML. Canvas draws 2D graphics, on the fly (with a JavaScript). SVG is vector based and composed of shapes. Canvas is raster based and composed of pixel.

Question: How do you serve a page with content in multiple languages?

> Answer: You serve a page with content in multiple languages by detecting the user's preferred language (usually from the browser settings), and then delivering the content in that language, which you've prepared and stored in advance. You can also make use of the `hreflang` attribute in the `<head>`.

```html
<!-- Example -->
<link rel="alternate" hreflang="de" href="http://de.example.com/page.html" />
```

Question: What are new in HTML5?

> Answer:

- Simplified Doctype: Introduced a standardized `<!DOCTYPE html>` declaration.
  Semantic Elements:
- Added semantic elements like `<header>`,`<nav>`,`<main>`,`<section>`,`<figure>`, `<footer>`,`<figcaption>`, `<article>`, `<aside>`,`<mark>`, `<details>`,`<summary>`,`<time>`.
- Audio and Video Support: Native support for `<audio>` and `<video>` elements, eliminating the need for plugins.
  Canvas Element: Introduced `<canvas>` for dynamic graphics and animations.
  - Local and Session Storage:
    Added localStorage and sessionStorage for persistent client-side storage.
  - Web Storage API:
    Provided a key-value storage mechanism for client-side data.
  - New Input Types:
    Introduced new input types (`<input type="date">`, `<input type="email">`, etc.).
  - New Form Attributes:
    Added form attributes like placeholder, autocomplete, and more.
  - Responsive Images:
    Introduced `<picture>` and `srcset` for responsive images.
  - Geolocation API:
    Enabled access to the user's geographical location.
- Web Workers: Allowed scripts to run in the background for concurrent processing.
- WebSockets: Provided a full-duplex communication channel for real-time communication.
- Drag and Drop API: Added native Drag and Drop API for interactive interfaces.
- Cross-document Messaging: Enabled secure communication between documents or frames.
- New Meta Tags: Added meta tags like `<meta charset="UTF-8">` and `<meta name="viewport">`.
