---
path: "/html-elements"
title: "HTML Elements"
section: "HTML"
order: 2
description: Welcome to Foundations of Design Systems!
---

# HTML Elements
An HTML file is made of elements. These elements are responsible for creating web pages and define content in that webpage. An element in HTML usually consist of a start tag `<tag name>`, close tag `</tag name>` and content inserted between them.  **Technically, an element is a collection of start tag, attributes, end tag, content between them**.

### Document metadata

Metadata contains information about the page. This includes information about styles, scripts and data to help software ([search engines](https://developer.mozilla.org/en-US/docs/Glossary/search_engine),  [browsers](https://developer.mozilla.org/en-US/docs/Glossary/Browser), etc.) use and render the page. Metadata for styles and scripts may be defined in the page or link to another file that has the information.

|Element|Description|
|--|--|
|[`<base>`]| The HTML <base> element specifies the base URL to use for all relative URLs in a document.
|[`<head>`]|The HTML <head> element contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets.
|[`<link>`]|The HTML External Resource Link element `(<link>)` specifies relationships between the current document and an external resource. This element is most commonly used to link to stylesheets, but is also used to establish site icons (both "favicon" style icons and icons for the home screen and apps on mobile devices) among other things.
|[`<meta>`]|The HTML <meta> element represents metadata that cannot be represented by other HTML meta-related elements, like `<base>, <link>, <script>, <style> or <title>.`
|[`<style>`]|The HTML `<style>` element contains style information for a document, or part of a document. 
|[`<title>`]|The HTML Title element `(<title>)` defines the document's title that is shown in a browser's title bar or a page's tab.

### Sectioning root
|Element|Description|
|--|--|
|[`<body>`]|The HTML `<body>` Element represents the content of an HTML document. There can be only one <body> element in a document.

### Content sectioning
|Element|Description|
|--|--|
|[`<address>`]|The HTML `<address>` element indicates that the enclosed HTML provides contact information for a person or people, or for an organization.
|[`<article>`]|The HTML `<article>` element represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication).
|[`<aside>`]|The HTML <aside> element represents a portion of a document whose content is only indirectly related to the document's main content.
|[`<footer>`]|The HTML `<footer>` element represents a footer for its nearest sectioning content or sectioning root element. A footer typically contains information about the author of the section, copyright data or links to related documents.
|[`<header>`]|The HTML `<header>` element represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements.
|[`<hgroup>`]|The HTML `<hgroup>` element represents a multi-level heading for a section of a document. It groups a set of `<h1>–<h6>` elements.
|[`<main>`]|The HTML `<main>` element represents the dominant content of the `<body>` of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.
|[`<nav>`]|The HTML  `<nav>`  element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.
|`[<section>`]|The HTML  `<section>`  element represents a standalone section — which doesn't have a more specific semantic element to represent it — contained within an HTML document.
### Text content
|Element|Descripion|
|--|--|
|[`<dd>`]|The HTML `<dd>` element provides the description, definition, or value for the preceding term `<dt>` in a description list `<dl>`
|[`<div>`]|The HTML Content Division element (`<div>`) is the generic container for flow content. It has no effect on the content or layout until styled using CSS.
|[`<dl>`]|The HTML `<dl>` element represents a description list. The element encloses a list of groups of terms (specified using the `<dt>` element) and descriptions (provided by `<dd>` elements). Common uses for this element are to implement a glossary or to display metadata (a list of key-value pairs).
|[`<dt>`]|The HTML `<dt>` element specifies a term in a description or definition list, and as such must be used inside a `<dl>` element.
|[`<figure>`]|The HTML `<figure>` (Figure With Optional Caption) element represents self-contained content, potentially with an optional caption, which is specified using the `(<figcaption>)` element.
|[`<li>`]|The HTML `<li>` element is used to represent an item in a list.
|[`<pre>`]|The HTML  `<pre>` element represents preformatted text which is to be presented exactly as written in the HTML file.
|[`<ul>`]|The HTML `<ul>` element represents an unordered list of items, typically rendered as a bulleted list.

### Table content
|Element|Description|
|--|--|
|[`<caption>`]|The HTML <caption> element specifies the caption (or title) of a table.
|[`<table>`]|The HTML `<table>` element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.
|[`<tbody>`]|The HTML Table Body element (`<tbody>`) encapsulates a set of table rows (`<tr>` elements), indicating that they comprise the body of the table (`<table>`).
|[`<td>`]|The HTML `<td>` element defines a cell of a table that contains data. It participates in the table model.
|[`<th>`]|The HTML `<th>` element defines a cell as header of a group of table cells. The exact nature of this group is defined by the scope and headers attributes.
|[`<thead>`]|The HTML `<thead>` element defines a set of rows defining the head of the columns of the table.
|[`<tr>`]|The HTML `<tr>` element defines a row of cells in a table. The row's cells can then be established using a mix of `<td>` (data cell) and `<th>` (header cell) elements.
### Image and multimedia
|Element|Description|
|--|--|
|[`<audio>`]|The HTML `<audio>` element is used to embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the `<source>` element: the browser will choose the most suitable one. It can also be the destination for streamed media, using a MediaStream.
|[`<img>`]|The HTML `<img>` element embeds an image into the document.
|[`<map>`]|The HTML <map> element is used with <area> elements to define an image map (a clickable link area).
|[`<track>`]|The HTML <track> element is used as a child of the media elements, <audio> and <video>. It lets you specify timed text tracks (or time-based data), for example to automatically handle subtitles.
|[`<video>`]|The HTML Video element (<video>) embeds a media player which supports video playback into the document. You can use <video> for audio content as well, but the <audio> element may provide a more appropriate user experience.
|[`<area>`]|The HTML <area> element defines a hot-spot region on an image, and optionally associates it with a hypertext link. This element is used only within a <map> element.
### Inline text semantics
|Element|Description|
|--|--|
|[`<a>`]|The HTML `<a>` element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.
|[`<data>`]|The HTML `<data>` element links a given piece of content with a machine-readable translation. If the content is time- or date-related, the `<time>` element must be used.
|[`<em>`]|The HTML `<em>` element marks text that has stress emphasis. The `<em>` element can be nested, with each level of nesting indicating a greater degree of emphasis.
|[`<mark>`]|The HTML Mark Text element (`<mark>`) represents text which is marked or highlighted for reference or notation purposes, due to the marked passage's relevance or importance in the enclosing context.
|[`<span>`]|The HTML `<span>` element is a generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang.
|[`<sub>`]|The HTML Subscript element (`<sub>`) specifies inline text which should be displayed as subscript for solely typographical reasons.
|[`<sup>`]|The HTML Superscript element (`<sup>`) specifies inline text which is to be displayed as superscript for solely typographical reasons.


#### References
[https://www.htmlquick.com/reference/tags.html](https://www.htmlquick.com/reference/tags.html)
[https://www.tutorialrepublic.com/html-reference/html5-tags.php](https://www.tutorialrepublic.com/html-reference/html5-tags.php)
[https://eastmanreference.com/complete-list-of-html-tags](https://eastmanreference.com/complete-list-of-html-tags)
