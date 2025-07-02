<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>What is a Front-End Developer?</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="navbar">
        <div class="logo">LEARN HUB</div>
        <div>
            <a href="index.html" class="active">Front-End Dev</a>
            <a href="what-is-html.html">HTML</a>
            <a href="what-is-css.html">CSS</a>
        </div>
    </div>

    <div class="container">
        <div class="sidebar">
            <h3>Front-End Topics</h3>
            <ul>
                <li><a href="index.html" class="active">What is Front-End Dev?</a></li>
                <li><a href="what-is-html.html">What is HTML?</a></li>
                <li><a href="what-is-css.html">What is CSS?</a></li>
                <li><a href="#javascript">What is JavaScript? (Coming Soon)</a></li>
                <li><a href="#frameworks">Front-End Frameworks (Coming Soon)</a></li>
            </ul>
            <h3>Related Technologies</h3>
            <ul>
                <li><a href="#react">React (Coming Soon)</a></li>
                <li><a href="#angular">Angular (Coming Soon)</a></li>
                <li><a href="#vue">Vue.js (Coming Soon)</a></li>
            </ul>
        </div>

        <div class="main-content">
            <h1>What is a Front-End Developer?</h1>
            <p>A Front-End Developer is someone who creates websites and web applications.</p>
            <p>The difference between Front-End and Back-End is that Front-End refers to how a web page looks, while Back-End refers to how it works.</p>
            <p>You can think of Front-End as <strong>client-side</strong> and Back-End as <strong>server-side</strong>.</p>
            <p>The basic languages for Front-End Development are HTML, CSS, and JavaScript.</p>

            <h2>Main responsibilities</h2>
            <p>The main responsibility of the Front-End Developer is the <strong>User Interface</strong>.</p>
            <ul>
                <li>Implementing web design into code.</li>
                <li>Ensuring the website is responsive and works well on all devices.</li>
                <li>Optimizing web pages for maximum speed and scalability.</li>
                <li>Working with back-end developers to integrate server-side logic.</li>
                <li>Maintaining and improving website performance.</li>
            </ul>

            <h2>Essential Skills</h2>
            <p>To become a successful Front-End Developer, you need to master several key technologies and concepts:</p>
            <ul>
                <li><strong>HTML (HyperText Markup Language):</strong> For structuring content.</li>
                <li><strong>CSS (Cascading Style Sheets):</strong> For styling the appearance.</li>
                <li><strong>JavaScript:</strong> For adding interactivity and dynamic behavior.</li>
                <li>Responsive Design: Building websites that adapt to different screen sizes.</li>
                <li>Version Control (e.g., Git): For tracking changes in code.</li>
                <li>Knowledge of browser developer tools.</li>
            </ul>

            <div class="buttons">
                <a href="#" class="prev-button">« Previous</a>
                <a href="what-is-html.html" class="next-button">Next »</a>
            </div>
        </div>

        <div class="ad-section">
            <h3>W3Schools Certification Courses</h3>
            <p>Learn to code with the world's largest web developer site.</p>
            <a href="#" style="background-color: #4CAF50; padding: 3px 10px; color: white; text-decoration: none; border-radius: 3px;">Check it out!</a>
            <img src="image\adv.jpg" alt="Advertisement">
        
        </div>
    </div>
</body>
</html>

[Uploading what-is-html.html…]()<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>What is HTML?</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="navbar">
        <div class="logo">LEARN HUB</div>
        <div>
            <a href="index.html">Front-End Dev</a>
            <a href="what-is-html.html" class="active">HTML</a>
            <a href="what-is-css.html">CSS</a>
        </div>
    </div>

    <div class="container">
        <div class="sidebar">
            <h3>Front-End Topics</h3>
            <ul>
                <li><a href="index.html">What is Front-End Dev?</a></li>
                <li><a href="what-is-html.html" class="active">What is HTML?</a></li>
                <li><a href="what-is-css.html">What is CSS?</a></li>
                <li><a href="#javascript">What is JavaScript? (Coming Soon)</a></li>
                <li><a href="#frameworks">Front-End Frameworks (Coming Soon)</a></li>
            </ul>
            <h3>Related Technologies</h3>
            <ul>
                <li><a href="#react">React (Coming Soon)</a></li>
                <li><a href="#angular">Angular (Coming Soon)</a></li>
                <li><a href="#vue">Vue.js (Coming Soon)</a></li>
            </ul>
        </div>

        <div class="main-content">
            <h1>What is HTML?</h1>
            <p><strong>HTML</strong> stands for <strong>HyperText Markup Language</strong>. It is the standard markup language for creating web pages.</p>
            <p>HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.</p>
            <p>HTML elements are the building blocks of HTML pages. With HTML constructs, images and other objects such as interactive forms may be embedded into the rendered page. It provides a means to create structured documents by denoting structural semantics for text such as headings, paragraphs, lists, links, quotes and other items.</p>

            <h2>Basic HTML Document Structure</h2>
            <p>A typical HTML document looks like this:</p>
            <pre><code>
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
    &lt;title&gt;Page Title&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;This is a Heading&lt;/h1&gt;
    &lt;p&gt;This is a paragraph.&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;
            </code></pre>

            <h2>Key HTML Tags</h2>
            <ul>
                <li><code>&lt;html&gt;</code>: The root element of an HTML page.</li>
                <li><code>&lt;head&gt;</code>: Contains meta-information about the HTML page (e.g., title, links to CSS).</li>
                <li><code>&lt;body&gt;</code>: Contains the visible page content.</li>
                <li><code>&lt;h1&gt;</code> to <code>&lt;h6&gt;</code>: Headings.</li>
                <li><code>&lt;p&gt;</code>: Paragraphs.</li>
                <li><code>&lt;a&gt;</code>: Links (anchors).</li>
                <li><code>&lt;img&gt;</code>: Images.</li>
                <li><code>&lt;ul&gt;</code>, <code>&lt;ol&gt;</code>, <code>&lt;li&gt;</code>: Unordered lists, ordered lists, list items.</li>
                <li><code>&lt;div&gt;</code>, <code>&lt;span&gt;</code>: Generic container elements for grouping content.</li>
            </ul>

            <div class="buttons">
                <a href="index.html" class="prev-button">« Previous</a>
                <a href="what-is-css.html" class="next-button">Next »</a>
            </div>
        </div>

        <div class="ad-section">
            <h3>Boost Your Skills!</h3>
            <p>Explore more courses on HTML5 and web development.</p>
            <a href="#" style="background-color: #28a745; padding: 1px 5px; color: white; text-decoration: none; border-radius: 3px;">Learn HTML Now!</a>
            <img src="image\adv.jpg" alt="HTML Advertisement">
            
        </div>
    </div>
</body>
</html>

[Uploading what-is-css.html…]()<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>What is CSS?</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="navbar">
        <div class="logo">LEARN HUB</div>
        <div>
            <a href="index.html">Front-End Dev</a>
            <a href="what-is-html.html">HTML</a>
            <a href="what-is-css.html" class="active">CSS</a>
        </div>
    </div>

    <div class="container">
        <div class="sidebar">
            <h3>Front-End Topics</h3>
            <ul>
                <li><a href="index.html">What is Front-End Dev?</a></li>
                <li><a href="what-is-html.html">What is HTML?</a></li>
                <li><a href="what-is-css.html" class="active">What is CSS?</a></li>
                <li><a href="#javascript">What is JavaScript? (Coming Soon)</a></li>
                <li><a href="#frameworks">Front-End Frameworks (Coming Soon)</a></li>
            </ul>
            <h3>Related Technologies</h3>
            <ul>
                <li><a href="#react">React (Coming Soon)</a></li>
                <li><a href="#angular">Angular (Coming Soon)</a></li>
                <li><a href="#vue">Vue.js (Coming Soon)</a></li>
            </ul>
        </div>

        <div class="main-content">
            <h1>What is CSS?</h1>
            <p><strong>CSS</strong> stands for <strong>Cascading Style Sheets</strong>. It is used to style the look and feel of web pages written in HTML.</p>
            <p>CSS describes how HTML elements are to be displayed on screen, paper, or in other media. It saves a lot of work. It can control the layout of multiple web pages all at once.</p>

            <h2>How CSS Works</h2>
            <p>CSS works by associating style rules with HTML elements. A style rule consists of a selector and a declaration block:</p>
            <pre><code>
selector {
    property: value;
    property: value;
}
            </code></pre>
            <p>For example, to change the color of all paragraphs to blue and set their font size to 16 pixels:</p>
            <pre><code>
p {
    color: blue;
    font-size: 16px;
}
            </code></pre>

            <h2>Ways to Include CSS</h2>
            <p>There are three ways to insert a style sheet:</p>
            <ul>
                <li><strong>External style sheet:</strong> The most common method. CSS is written in a separate `.css` file and linked to the HTML document using the <code>&lt;link&gt;</code> tag in the <code>&lt;head&gt;</code> section. This is what we are using in this example (`style.css`).</li>
                <li><strong>Internal style sheet:</strong> CSS is written within <code>&lt;style&gt;</code> tags inside the <code>&lt;head&gt;</code> section of an HTML document.</li>
                <li><strong>Inline style:</strong> CSS is applied directly to an HTML element using the `style` attribute. This is generally discouraged for larger projects as it mixes content and presentation.</li>
            </ul>

            <h2>CSS Selectors</h2>
            <p>CSS selectors are used to "find" (or select) the HTML elements you want to style.</p>
            <ul>
                <li><strong>Element Selector:</strong> Selects HTML elements based on their name (e.g., `p`, `h1`).</li>
                <li><strong>ID Selector:</strong> Selects an element with a specific `id`. IDs must be unique within a page (e.g., `#myHeader`).</li>
                <li><strong>Class Selector:</strong> Selects elements with a specific `class`. Classes can be used multiple times on a page (e.g., `.myClass`).</li>
                <li><strong>Universal Selector:</strong> Selects all HTML elements on the page (e.g., `*`).</li>
            </ul>

            <div class="buttons">
                <a href="what-is-html.html" class="prev-button">« Previous</a>
                <a href="#" class="next-button">Next » (Coming Soon)</a>
            </div>
        </div>

        <div class="ad-section">
            <h3>Master CSS!</h3>
            <p>Design beautiful and responsive websites with our CSS tutorials.</p>
            <a href="#" style="background-color: #dc3545; padding: 1px 5px; color: white; text-decoration: none; border-radius: 3px;">Start Learning CSS!</a>
            <img src="image\adv.jpg" alt="CSS Advertisement">
            <p>Transform your web pages.</p>
        </div>
    </div>
</body>
</html>

[Uploading style.css…]()body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

.navbar {
    background-color: #333;
    overflow: hidden;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.navbar a {
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

.navbar a:hover {
    background-color: #ddd;
    color: black;
}

.navbar .logo {
    font-size: 24px;
    font-weight: bold;
}

.container {
    display: flex;
    max-width: 1200px;
    margin: 20px auto;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
}

.sidebar {
    width: 250px;
    padding: 20px;
    background-color: #f4f4f4;
    border-right: 1px solid #eee;
}

.sidebar h3 {
    margin-top: 0;
    color: #555;
}

.sidebar ul {
    list-style-type: none;
    padding: 0;
}

.sidebar ul li a {
    display: block;
    padding: 10px 0;
    text-decoration: none;
    color: #333;
    border-bottom: 1px solid #eee;
}

.sidebar ul li a:hover,
.sidebar ul li a.active {
    background-color: #ddd;
    color: #000;
}

.main-content {
    flex-grow: 1;
    padding: 20px 40px;
}

.main-content h1 {
    color: #333;
    border-bottom: 2px solid #007bff;
    padding-bottom: 10px;
    margin-bottom: 20px;
}

.main-content h2 {
    color: #555;
    margin-top: 30px;
}

.main-content p {
    line-height: 1.6;
    color: #666;
}

.main-content ul {
    list-style-type: disc;
    margin-left: 20px;
    color: #666;
}

.main-content ul li {
    margin-bottom: 10px;
}

.buttons {
    margin-top: 30px;
    display: flex;
    justify-content: space-between;
}

.buttons a {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.buttons a:hover {
    background-color: #0056b3;
}

.ad-section {
    width: 250px;
    padding: 20px;
    background-color: #f9f9f9;
    border-left: 1px solid #eee;
    text-align: center;
}

.ad-section img {
    max-width: 100%;
    height: auto;
    margin-top: 20px;
    border-radius: 8px;
}

.ad-section p {
    color: #888;
    font-style: italic;
}

/* Responsive adjustments */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
    .sidebar {
        width: 100%;
        border-right: none;
        border-bottom: 1px solid #eee;
    }
    .ad-section {
        width: 100%;
        border-left: none;
        border-top: 1px solid #eee;
    }
}

![adv](https://github.com/user-attachments/assets/e16a245c-7d09-4251-a189-b09767767a10)
![adv](https://github.com/user-attachments/assets/87d0da62-ca07-400a-aac4-b34d4ea3182d)



