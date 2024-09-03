# 1. HTML Review - Basic Elements
## 1.A HTML Structure

```
<!DOCTYPE html>
<html>
  <head></head>
  <body></body>
</html>
```

Using the following basic structure, **browsers** will know that the file it is parsing/reading is a valid **HTML** file

---

## 1.B `<head>` - The Document "Metadatada" (Header) element

This element will contain machine-readable information (metadata) about the HTML document, like its **title**, **scripts**, and **style sheets**.

> There can only be one `<head>` element in an HTML document

Here are the elements that can be used inside the `<head>` element:

| Element | Description | Attributes | Examples |
| :--- | :--- | :--- | --- |
| `title` | sets the document's title as shown on a browser's title bar | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title#examples) |
| `base` | specifies the base URL to use for all <i>relative</i> URLs in a document | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base#examples) |
| `link` | specifies relationships between the current document and an external resource. This element is most commonly used to link to **stylesheets**, but is also used to establish **site icons** (both "favicon" style icons and icons for the home screen and apps on mobile devices) | [link]() | [link]() |
| `style` | contains style information for a document, or part of a document. It contains CSS, which is applied to the contents of the document containing the `<style>` element. It is most commonly known as "internal style sheet" | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link#examples) |
| `meta` | represents metadata that cannot be represented by other HTML meta-related elements, like `<base>`, `<link>`, `<script>`, `<style>` or `<title>` | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#examples) |
| `script` | used to embed executable code or data; this is typically used to embed or refer to `JavaScript` code. | [link]() |
| `noscript` | defines a section of HTML to be inserted if a script type on the page is unsupported or if scripting is currently turned off in the browser. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noscript#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#examples) |
| `template` | serves as a mechanism for holding HTML fragments, which can either be used later via <code>JavaScript</code> or generated immediately into shadow DOM. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template#examples) |

---

## 1.C `<body>` - The Document Body element

The `<body>` HTML element represents the content of an HTML document. There can be only one `<body>` element in a document.

* [List of Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body#attributes)
* [Examples](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body#examples)

---

## 1.D Content Sectioning

Content sectioning elements allow you to organize the document content into logical pieces. Use the sectioning elements to create a broad outline for your page content, including header and footer navigation, and heading elements to identify sections of content.

| Element | Description | Attributes | Examples |
| :--- | :--- | :--- | --- |
`address` |	Indicates that the enclosed HTML provides contact information for a person or people, or for an organization. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address#examples)
`article` |	Represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include a forum post, a magazine or newspaper article, a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article#examples)
`aside` |	Represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside#examples)
`footer` |	Represents a footer for its nearest ancestor sectioning content or sectioning root element. A `footer` typically contains information about the author of the section, copyright data, or links to related documents.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer#examples)
`header` |	Represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header#examples)
`h1`, `h2`, `h3`, `h4`, `h5`, `h6` |	Represent six levels of section headings. `h1` is the highest section level and `h6` is the lowest.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements#examples)
`hgroup` |	Represents a heading grouped with any secondary content, such as subheadings, an alternative title, or a tagline.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hgroup#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hgroup#examples)
`main` |	Represents the dominant content of the body of a document. The main content area consists of content that is directly related to or expands upon the central topic of a document, or the central functionality of an application.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main#examples)
`nav` |	Represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav#examples)
`section` |	Represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections should always have a heading, with very few exceptions.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section#examples)
`search` |	Represents a part that contains a set of form controls or other content related to performing a search or filtering operation.| [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/search#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/search#examples)

---

## 1.E Text Coontent

Use HTML text content elements to organize blocks or sections of content placed between the opening `<body>` and closing `</body>` tags. Important for accessibility and SEO, these elements identify the purpose or structure of that content.

| Element | Description | Attributes | Examples |
| :--- | :--- | :--- | --- |
`blockquote` |	Indicates that the enclosed text is an extended quotation. Usually, this is rendered visually by indentation. A URL for the source of the quotation may be given using the cite attribute, while a text representation of the source can be given using the `cite` element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote#examples)
`dd` |	Provides the description, definition, or value for the preceding term (`dt`) in a description list (`dl`). | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dd#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dd#examples)
`div` |	The generic container for flow content. It has no effect on the content or layout until styled in some way using CSS (e.g., styling is directly applied to it, or some kind of layout model like flexbox is applied to its parent element). | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div#examples)
`dl` |	Represents a description list. The element encloses a list of groups of terms (specified using the `dt` element) and descriptions (provided by `dd` elements). Common uses for this element are to implement a glossary or to display metadata (a list of key-value pairs). | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl#examples)
`dt` |	Specifies a term in a description or definition list, and as such must be used inside a `dl` element. It is usually followed by a `dd` element; however, multiple `dt` elements in a row indicate several terms that are all defined by the immediate next `dd` element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dt#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dt#examples)
`figcaption` |	Represents a caption or legend describing the rest of the contents of its parent `figure` element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption#examples)
`figure` |	Represents self-contained content, potentially with an optional caption, which is specified using the `figcaption` element. The figure, its caption, and its contents are referenced as a single unit. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure#examples)
`hr` |	Represents a thematic break between paragraph-level elements: for example, a change of scene in a story, or a shift of topic within a section. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr#examples)
`li` |	Represents an item in a list. It must be contained in a parent element: an ordered list (`ol`), an unordered list (`ul`), or a menu (`menu`). In menus and unordered lists, list items are usually displayed using bullet points. In ordered lists, they are usually displayed with an ascending counter on the left, such as a number or letter. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li#examples)
`menu` |	A semantic alternative to `ul`, but treated by browsers (and exposed through the accessibility tree) as no different than `ul`. It represents an unordered list of items (which are represented by `li` elements). | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menu#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menu#examples)
`ol` |	Represents an ordered list of items — typically rendered as a numbered list. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol#examples)
`p` |	Represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p#examples)
`pre` |	Represents preformatted text which is to be presented exactly as written in the HTML file. The text is typically rendered using a non-proportional, or monospaced, font. Whitespace inside this element is displayed as written. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre#examples)
`ul` |	Represents an unordered list of items, typically rendered as a bulleted list. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul#examples)

---

## 1.F Inline Text Semantics

Use the HTML inline text semantic to define the meaning, structure, or style of a word, line, or any arbitrary piece of text.

| Element | Description | Attributes | Examples |
| :--- | :--- | :--- | --- |
`a` |	Together with its href attribute, creates a hyperlink to web pages, files, email addresses, locations within the current page, or anything else a URL can address. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#examples)
`abbr` |	Represents an abbreviation or acronym. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/abbr#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/abbr#examples)
`b` |	Used to draw the reader's attention to the element's contents, which are not otherwise granted special importance. This was formerly known as the Boldface element, and most browsers still draw the text in boldface. However, you should not use `b` for styling text or granting importance. If you wish to create boldface text, you should use the CSS font-weight property. If you wish to indicate an element is of special importance, you should use the strong element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b#examples)
`bdi` |	Tells the browser's bidirectional algorithm to treat the text it contains in isolation from its surrounding text. It's particularly useful when a website dynamically inserts some text and doesn't know the directionality of the text being inserted. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/bdi#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/bdi#examples)
`bdo` |	Overrides the current directionality of text, so that the text within is rendered in a different direction. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/bdo#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/bdo#examples)
`br` |	Produces a line break in text (carriage-return). It is useful for writing a poem or an address, where the division of lines is significant. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br#examples)
`cite` |	Used to mark up the title of a cited creative work. The reference may be in an abbreviated form according to context-appropriate conventions related to citation metadata. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/cite#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/cite#examples)
`code` |	Displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code. By default, the content text is displayed using the user agent's default monospace font. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/code#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/code#examples)
`data` |	Links a given piece of content with a machine-readable translation. If the content is time- or date-related, the `time` element must be used. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/data#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/data#examples)
`dfn` |	Used to indicate the term being defined within the context of a definition phrase or sentence. The ancestor `p` element, the `dt`/`dd` pairing, or the nearest section ancestor of the `dfn` element, is considered to be the definition of the term. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dfn#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dfn#examples)
`em` |	Marks text that has stress emphasis. The `em` element can be nested, with each nesting level indicating a greater degree of emphasis. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em#examples)
`i` |	Represents a range of text that is set off from the normal text for some reason, such as idiomatic text, technical terms, and taxonomical designations, among others. Historically, these have been presented using italicized type, which is the original source of the `i` naming of this element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i#examples)
`kbd` |	Represents a span of inline text denoting textual user input from a keyboard, voice input, or any other text entry device. By convention, the user agent defaults to rendering the contents of a `kbd` element using its default monospace font, although this is not mandated by the HTML standard. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd#examples)
`mark` |	Represents text which is marked or highlighted for reference or notation purposes due to the marked passage's relevance in the enclosing context. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/mark#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/mark#examples)
`q` |	Indicates that the enclosed text is a short inline quotation. Most modern browsers implement this by surrounding the text in quotation marks. This element is intended for short quotations that don't require paragraph breaks; for long quotations use the `blockquote` element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q#examples)
`rp` |	Used to provide fall-back parentheses for browsers that do not support the display of ruby annotations using the `ruby` element. One `rp` element should enclose each of the opening and closing parentheses that wrap the `rt` element that contains the annotation's text. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rp#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rp#examples)
`rt` |	Specifies the ruby text component of a ruby annotation, which is used to provide pronunciation, translation, or transliteration information for East Asian typography. The `rt` element must always be contained within a `ruby` element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rt#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rt#examples)
`ruby` |	Represents small annotations that are rendered above, below, or next to base text, usually used for showing the pronunciation of East Asian characters. It can also be used for annotating other kinds of text, but this usage is less common. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ruby#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ruby#examples)
`s` |	Renders text with a strikethrough, or a line through it. Use the `s` element to represent things that are no longer relevant or no longer accurate. However, `s` is not appropriate when indicating document edits; for that, use the `del` and `ins` elements, as appropriate. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/s#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/s#examples)
`samp` |	Used to enclose inline text which represents sample (or quoted) output from a computer program. Its contents are typically rendered using the browser's default monospaced font (such as Courier or Lucida Console). | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/samp#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/samp#examples)
`small` |	Represents side-comments and small print, like copyright and legal text, independent of its styled presentation. By default, it renders text within it one font size smaller, such as from small to x-small. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/small#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/small#examples)
`span` |	A generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element is appropriate. `span` is very much like a div element, but div is a block-level element whereas a `span` is an inline-level element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span#examples)
`strong` |	Indicates that its contents have strong importance, seriousness, or urgency. Browsers typically render the contents in bold type. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong#examples)
`sub` |	Specifies inline text which should be displayed as subscript for solely typographical reasons. Subscripts are typically rendered with a lowered baseline using smaller text. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sub#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sub#examples)
`sup` |	Specifies inline text which is to be displayed as superscript for solely typographical reasons. Superscripts are usually rendered with a raised baseline using smaller text. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sup#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sup#examples)
`time` |	Represents a specific period in time. It may include the datetime attribute to translate dates into machine-readable format, allowing for better search engine results or custom features such as reminders. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time#examples)
`u` |	Represents a span of inline text which should be rendered in a way that indicates that it has a non-textual annotation. This is rendered by default as a simple solid underline but may be altered using CSS. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/u#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/u#examples)
`var` |	Represents the name of a variable in a mathematical expression or a programming context. It's typically presented using an italicized version of the current typeface, although that behavior is browser-dependent. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/var#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/var#examples)
`wbr` |	Represents a word break opportunity—a position within text where the browser may optionally break a line, though its line-breaking rules would not otherwise create a break at that location. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/wbr#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/wbr#examples)

---

## 1.G Table Content

The elements here are used to create and handle tabular data.

| Element | Description | Attributes | Examples |
| :--- | :--- | :--- | --- |
`caption` |	Specifies the caption (or title) of a table. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption#examples)
`col` |	Defines one or more columns in a column group represented by its implicit or explicit parent `colgroup` element. The `col` element is only valid as a child of a `colgroup` element that has no span attribute defined. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/col#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/col#examples)
`colgroup` |	Defines a group of columns within a table. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/colgroup#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/colgroup#examples)
`table` |	Represents tabular data—that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table#examples)
`tbody` |	Encapsulates a set of table rows (`tr` elements), indicating that they comprise the body of a table's (main) data. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody#examples)
`td` |	A child of the `tr` element, it defines a cell of a table that contains data. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td#examples)
`tfoot` |	Encapsulates a set of table rows (`tr` elements), indicating that they comprise the foot of a table with information about the table's columns. This is usually a summary of the columns, e.g., a sum of the given numbers in a column. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot#examples)
`th` |	A child of the `tr` element, it defines a cell as the header of a group of table cells. The nature of this group can be explicitly defined by the scope and headers attributes. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th#examples)
`thead` |	Encapsulates a set of table rows (`tr` elements), indicating that they comprise the head of a table with information about the table's columns. This is usually in the form of column headers (`th` elements). | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead#examples)
`tr` |	Defines a row of cells in a table. The row's cells can then be established using a mix of `td` (data cell) and `th` (header cell) elements. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr#examples)

---

## 1.H Forms

HTML provides several elements that can be used together to create forms that the user can fill out and submit to the website or application. 

| Element | Description | Attributes | Examples |
| :--- | :--- | :--- | --- |
`button` |	An interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it performs an action, such as submitting a form or opening a dialog. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button#examples)
`datalist` |	Contains a set of `option` elements that represent the permissible or recommended options available to choose from within other controls. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist#examples)
`fieldset` |	Used to group several controls as well as labels (`label`) within a web form. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/fieldset#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/fieldset#examples)
`form` |	Represents a document section containing interactive controls for submitting information. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#examples)
`input` |	Used to create interactive controls for web-based forms to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The `input` element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#examples)
`label` |	Represents a caption for an item in a user interface. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label#examples)
`legend` |	Represents a caption for the content of its parent `fieldset`.  | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/legend#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/legend#examples)
`meter` |	Represents either a scalar value within a known range or a fractional value. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meter#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meter#examples)
`optgroup` |	Creates a grouping of options within a `select` element. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/optgroup#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/optgroup#examples)
`option` |	Used to define an item contained in a select, an `optgroup`, or a `datalist` element. As such, `option` can represent menu items in popups and other lists of items in an HTML document. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option#examples)
`output` |	Container element into which a site or app can inject the results of a calculation or the outcome of a user action. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/output#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/output#examples)
`progress` |	Displays an indicator showing the completion progress of a task, typically displayed as a progress bar. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/progress#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/progress#examples)
`select` |	Represents a control that provides a menu of options. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select#examples)
`textarea` |	Represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example, a comment on a review or feedback form. | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea#attributes) | [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea#examples)

---