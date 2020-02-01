## HTML

 - HTML5 does not require empty elements(`<br>`) to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.
 - HTML tags are not case sensitive ` <P>` means the same as `<p>`.
 - The HTML5 standard does not require lowercase tags, but W3C **recommends** lowercase in HTML, and **demands** lowercase for stricter document types like XHTML.
 - **Attribute** : HTML links are defined with the `<a>` tag. The link address is specified in the `href` attribute
 - The HTML `<head>` element is a container for metadata. HTML metadata is data about the HTML document. Metadata is not displayed. `<meta charset="UTF-8">`
 - Browsers automatically add some white space (a margin) before and after a paragraph.
 - The text inside a **`<pre>`** element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.
 - Browsers display `<strong>` as `<b>`, and `<em>` as `<i>`. However, there is a difference in the meaning of these tags: `<b>` and `<i>` defines bold and italic text, but `<strong>` and `<em>` means that the text is "important".
 - Without a forward slash at the end of sub-folder addresses, you might generate two requests to the server. Many servers will automatically add a forward slash to the end of the address, and then create a new request.
 - ***In `<img>` Tag***, The `alt` attribute is required. A web page will not validate correctly without it.
 - ***In `<img>` Tag***,  Always specify the width and height of an image. If width and height are not specified, the page might flicker while the image loads.
 - ***In `<img>` Tag***, `border:0;` is added to prevent IE9 (and earlier) from displaying a border around the image (when the image is a link).
