# HTML5 Interview Questions &amp; Answers 2024

- Question: **What is the purpose of the `<!DOCTYPE html>` declaration?**
  > Answer: `<!DOCTYPE html>` is an instruction to the web browser about what version of HTML the page is written in. In HTML5, <!DOCTYPE html> is used to specify that the document is HTML5.
- Question: What is the difference between localStorage and sessionStorage objects?
  > Answer: Both localStorage and sessionStorage are part of the web storage API and are used to store data on the client side. The main difference is that localStorage has no expiration time, while sessionStorage gets cleared when the page session ends (i.e., when the page is closed).
- Question: What is the use of the canvas element in HTML5?
  > Answer: The canvas element is used to draw graphics on a web page that are on the fly via scripting (usually JavaScript). It can be used to draw graphs, make photo compositions, create animations, or even do real-time video processing or rendering.
- Question: What are data- attributes good for in HTML?
  > Answer: HTML5 introduced custom data attributes. They are used to store custom data private to the page or application. The stored data can then be used in the JavaScript to create a more interactive user experience.
- Question: What is the difference between SVG and Canvas?
  > Answer: SVG is a language for describing 2D graphics in XML. Canvas draws 2D graphics, on the fly (with a JavaScript). SVG is vector based and composed of shapes. Canvas is raster based and composed of pixel.
- Question: How do you serve a page with content in multiple languages?

  > Answer: You serve a page with content in multiple languages by detecting the user's preferred language (usually from the browser settings), and then delivering the content in that language, which you've prepared and stored in advance. You can also make use of the `hreflang` attribute in the `<head>`.

  ```html
  <!-- Example -->
  <link rel="alternate" hreflang="de" href="http://de.example.com/page.html" />
  ```

- Question: What is new in HTML5?

  > Answer Starts Here

  - Introduced a standardized `<!DOCTYPE html>` declaration.
    Semantic Elements:
  - Added semantic elements:
    - `<article>`
    - `<aside>`
    - `<details>`
    - `<figcaption>`
    - `<figure>`
    - `<footer>`
    - `<header>`
    - `<main>`
    - `<mark>`
    - `<nav>`
    - `<section>`
    - `<summary>`
    - `<time>`
  - Audio and Video Support: Native support for `<audio>` and `<video>` elements, eliminating the need for plugins.
  - Introduced `<canvas>` for dynamic graphics and animations.
  - Added **localStorage** and **sessionStorage** for persistent client-side storage.
  - Web Storage API: Provided a key-value storage mechanism for client-side data.
  - New Input Types:
    - `<input type="color">`
    - `<input type="date">`
    - `<input type="datetime-local">`
    - `<input type="email">`
    - `<input type="month">`
    - `<input type="number">`
    - `<input type="range">`
    - `<input type="search">`
    - `<input type="tel">`
    - `<input type="time">`
    - `<input type="url">`
    - `<input type="week">`
  - New Form Attributes:

    - `autocomplete`
    - `autofocus`
    - `form`
    - `formaction`
    - `formenctype`
    - `formmethod`
    - `formnovalidate`
    - `formtarget`
    - `height` and `width` attributes for `<th>` and `<td>` elements
    - `list` attribute for `<input>` and `<textarea>` elements
    - `min` and `max` attributes for `<input type="number">` and `<input type="range">`
    - `multiple` attribute for `<input>` elements of type `email` and `file`
    - `pattern` attribute for input validation
    - `placeholder` attribute for providing a hint to the user
    - `required` attribute for form validation
    - `step` attribute for `<input type="number">` and `<input type="range">`
    - `novalidate` attribute for turning off form validation

  - Responsive Images: Introduced `<picture>` and `srcset` for responsive images.
  - Geolocation API: Enabled access to the user's geographical location.

  - Web Workers: Allowed scripts to run in the background for concurrent processing.
  - WebSockets: Provided a full-duplex communication channel for real-time communication.
  - Drag and Drop API: Added native Drag and Drop API for interactive interfaces.
  - Cross-document Messaging: Enabled secure communication between documents or frames.
  - New Meta Tags: Added meta tags like `<meta charset="UTF-8">` and `<meta name="viewport">`.

  > Answer Ends Here

- Question: What is W3 validation and why is it necessary?
  > Answer: W3 validation ensures your code follows web standards for better compatibility and accessibility.
- Question: What are the errors of W3 validation?
  > Answer: Errors in W3 validation indicate issues in your code that may affect website performance or accessibility.
- Question: Why is the alt attribute used? Note: Besides displaying the alt text when an image fails to load, it has other important purposes.
  > Answer: The other important purposes of alt attribute is used for accessibility and SEO.
- Question: What is HTML canvas and how does it work?
  > Answer: HTML canvas is a feature for drawing graphics on a webpage dynamically which was introduced in HTML5.
- Question: Instead of the heading tag, we can use other tags and then we can style them through CSS but why is the heading tag still being used?
  > Answer: Using the actual heading tag instead of other tag is preferred for semantic and seo purposes.
- Question: How many times should the h1 tag be used in a webpage and why?
  > Answer: We should use the h1 tag once per webpage for the main heading to maintain proper document structure and SEO.
