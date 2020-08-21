---
path: "/html-sections"
title: "Sections of HTML Page"
section: "HTML"
order: 1
description: Welcome to Foundations of Design Systems!
---

# HTML Section Tag

The HTML `<section>` tag is used to define **sections in a document**. When you put your content on a web page, it may contains many **chapters, headers, footers, or other sections on a web page** that is why HTML `<section>` tag is used.

HTML `<section>` is a **new tag introduced in HTML5.**

-   **HTML Navigational Element**  ([`<nav>`]The HTML <nav> element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.")) defines a section that contains navigation links that appear often on a site. You can have primary and secondary menus, but you cannot nest a  `<nav>`  element inside another `<nav>`  element.
-   **HTML Article Element**  ([`<article>`]The HTML <article> element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication).")) defines a piece of self-contained content. It does not refer to the main content alone and can be used for comments and widgets.
-   **HTML Section Element**  ([`<section>`]The HTML <section> element represents a standalone section — which doesn't have a more specific semantic element to represent it — contained within an HTML document.")) defines a section of a document to indicate a related grouping of semantic meaning. It makes sense to use the section element to provide extra context for the parent element.
-   **HTML Aside Element**  ([`<aside>`]The HTML <aside> element represents a portion of a document whose content is only indirectly related to the document's main content.")) defines a section that, though related to the main element, doesn't belong to the main flow, like an explanation box or an advertisement. The aside element has its own outline, but doesn't belong to the main one.

```html
 <body>
    <header>
      <nav>
        <ul>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
        </ul>
      </nav>
      <h1>
        Page Title
      </h1>
    </header>
    <section>
      <h2>
        My Blog Posts
      </h2>
      <article>
        <header>
          <p>
            Article Title
          </p>
        </header>
        <p>
          content
        </p>
      </article>
      <article>
        <header>
          <p>
            Article Title
          </p>
        </header>
        <p>
          content
        </p>
      </article>
      <aside>
        <p>
          Author info
        </p>
      </aside>
    </section>
    <footer>
      Copyright Info
    </footer>
  </body>
```
