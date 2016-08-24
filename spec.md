Project Specification - Build a Portfolio Site
==============

## Project Overview

For this project, you'll be building a portfolio website. You will be provided a design mockup as a PDF-file, and you must replicate that design in HTML and CSS. You will develop a responsive website that will display images, descriptions and links to each of the portfolio projects.

Once you've successfully replicated the design mockup, you are encouraged to continue tweaking and making customizations to the design to personalize it and make it your own! This is your living portfolio site, so make sure you're happy with it.

## Design

<table>
    <thead>
        <tr>
            <th>Criteria</th>
            <th>Meets Specification</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Required Elements</td>
            <td>
                <p>The page at minimum includes all of the following:</p>
                <ul>
                    <li>at least 4 images</li>
                    <li>title text (h1, h2, etc.)</li>
                    <li>regular (paragraph) text</li>
                    <li>a logo.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Semantic HTML</td>
            <td>
                <p>HTML5 semantic tags such as <code>&lt;header&gt;</code>, <code>&lt;footer&gt;</code>, <code>&lt;article&gt;</code>, <code>&lt;section&gt;</code> etc. are used to add meaning to the code.</p>

                <p>No <code>&lt;div&gt;</code> or <code>&lt;section&gt;</code> tags are without a CSS class or id.</p>

                <p>Check out the W3C documentation on <a href="https://www.w3.org/wiki/HTML_structural_elements">HTML Structural Elements</a> to learn more!</p>
            </td>
        </tr>
        <tr>
            <td>Custom Design</td>
            <td>
                <p>Provide at least one of the following customizations:</p>
                <ul>
                    <li>Customize images and text.</li>
                    <li>Customize placement of the elements on the page (grid layout) with <code>HTML</code>, <code>CSS</code> or both.</li>
                    <li>Customize <code>CSS</code> styles applied at minimum to paragraph and heading elements.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Grid-Based Layout</td>
            <td>
                <p>Page utilizes a grid-based layout with styles making use of the <code>flexbox</code> layout or a framework like <code>Bootstrap</code>, <code>Foundation</code>, etc.</p>
                <p>If you're using <code>Bootstrap</code> or standard <code>HMTL/CSS</code>: the rows and columns of the grid must be wrapped in an element with a <code>container</code> class.</p>
            </td>
        </tr>
    </tbody>
</table>

## Responsiveness

<table>
    <thead>
        <tr>
            <th>Criteria</th>
            <th>Meets Specification</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cross-Device Compatibility</td>
            <td>
                <p>All content is responsive and displays on all display sizes. This includes:</p>
                <ul>
                    <li>Desktop</li>
                    <li>Mobile: Google Nexus 5</li>
                    <li>Tablet: Apple iPad</li>
                </ul>
                <p>An image's associated title and text renders next to the image in all viewport sizes.</p>

                <p>TIP: Test responsiveness with Chrome Developer Tools device emulation by right-clicking anywhere on page, selecting ‘Inspect Element’, clicking the rectangle to the left of the Elements tab, select Apple iPad or Google Nexus 5 from Device drop-down list, and click reload.</p>
            </td>
        </tr>
        <tr>
            <td>Provide All Content</td>
            <td>All content is rendered on all three devices. No content should be hidden on mobile devices. </td>
        </tr>
        <tr>
            <td>Viewport meta Tag</td>
            <td>Viewport <code>meta</code> tag is included in <code>HTML</code>. (i.e. <code>&lt;meta name=”viewport” …</code>)</td>
        </tr>
        <tr>
            <td>Responsive Images</td>
            <td>If a CSS framework is used, classes provided by the CSS framework are used to make images responsive, otherwise media-queries are used to ensure responsiveness of images.</td>
        </tr>
    </tbody>
</table>

## Separation of Concerns

<table>
    <thead>
        <tr>
            <th>Criteria</th>
            <th>Meets Specification</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Styles Separated From HTML</td>
            <td>
                <p>Portfolio completely separates structure (<code>HTML</code>) from design/style (<code>CSS</code>). There are no style attributes present in the body of the HTML document. There are no <code>&lt;style&gt;</code> elements in the document.</p>

                <p>Note: It is acceptable to include <code>height</code> and <code>width</code> attributes in <code>&lt;img&gt;</code> elements.</p>
            </td>
        </tr>
        <tr>
            <td>File structure</td>
            <td>
                <p>Files are organized with a directory structure that separates files based on functionality. For example:<br>
                <code>css/</code> for stylesheets<br>
                <code>img/</code> for images<br>
                <code>js/</code> for JavaScript files</p>
            </td>
        </tr>
    </tbody>
</table>

## Code Quality

<table>
    <thead>
        <tr>
            <th>Criteria</th>
            <th>Meets Specification</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>HTML Formatting rules</td>
            <td>
                <ul>
                    <li>All code ( <code>HTML</code> element names, attributes, attribute values) is lowercase (except <code>text/CDATA</code>).</li>
                    <li>Code does not have trailing white spaces.</li>
                    <li>Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).</li>
                    <li>Code uses a new line for every block, list or table element and indent every such child element (it's acceptable to put all <code>&lt;li&gt;</code> elements in one line).</li>
                    <li>[Optional] When quoting attribute values, code uses double quotation marks.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>HTML Style Rules</td>
            <td>
                <ul>
                    <li><code>HTML</code> documents use <code>HTML5</code> <code>&lt;!doctype html&gt;</code>.</li>
                    <li>Code passes <code>HTML</code> and <code>CSS</code> validators.</li>
                    <li>*[Optional] Code does not use entity references unless necessary e.g. characters with special meaning in <code>HTML</code> (like < and &) as well as control or “invisible” characters (like no-break spaces).</li>
                    <li>[Optional] Code omits type attributes for style sheets and scripts.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>CSS Formatting Rules</td>
            <td>
                <ul>
                    <li>Code does not have trailing white spaces.</li>
                    <li>Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).</li>
                    <li>Code indents all block content, that is rules within rules as well as declarations to reflect hierarchy and improve understanding.</li>
                    <li>Code uses a semicolon after every declaration for consistency and extensibility reasons.</li>
                    <li>Code always uses a space after a property name's colon, but no space between property and colon, for consistency reasons.</li>
                    <li>Code always use a single space between the last selector and the opening brace that begins the declaration block.</li>
                    <li>Code always start a new line for each selector and declaration.</li>
                    <li>Code always put a blank line (two line breaks) between rules.</li>
                    <li>[Optional] Code uses double quotation marks for attribute selectors or property values. Do not use quotation marks in <code>URI</code> values (<code>url()</code>).</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>CSS Style Rules</td>
            <td>
                <ul>
                    <li>Code uses meaningful or generic ID and class names that are as short as possible but as long as necessary.</li>
                    <li>Code does not use element names in conjunction with IDs or classes.</li>
                    <li>Code uses shorthand properties where possible.</li>
                    <li>[Optional] Code omits unit specification after 0 values.</li>
                    <li>[Optional] Code includes leading 0s in decimal values for readability.</li>
                    <li>[Optional] Code uses 3-character hexadecimal notation where possible.</li>
                    <li>[Optional] Code separate words in ID and class names by a hyphen.</li>
                    <li>[Optional] Code avoids user agent detection as well as <code>CSS</code> "hacks" — try a different approach first.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>General Meta Rules</td>
            <td>
                <ul>
                    <li><code>HTML</code> templates and documents use <code>UTF-8</code> encoding. (no <code>BOM</code>) i.e. <code>&lt;meta charset="utf-8"&gt;</code>.</li>
                    <li>*[Optional] Mark todos and action items with <code>TODO</code></li>
                </ul>
            </td>

        </tr>
    </tbody>
</table>

## Suggestions To Make Your Project Stand Out!

Use srcset in the img elements to provide optimized images to users on all devices.

Include additional JavaScript functionality, while maintaining required components. For example: Bootstrap Navbar, Polymer Components.