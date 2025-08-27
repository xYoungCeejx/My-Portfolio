<!DOCTYPE html>
<html>
   <head>
       <title>My portfolio</title>
       <style>
           body {
               background: #000;
               color: #e0e0e0;
               font-family: 'Segoe UI', Arial, sans-serif;
               margin: 0;
               padding: 32px 0 32px 0;
           }
           .main-content {
               max-width: 900px;
               margin: 0 auto;
               padding: 0 32px;
               background: rgba(30,30,30,0.95);
               border-radius: 18px;
               box-shadow: 0 8px 32px rgba(0,0,0,0.7);
           }
           h1 {
               color: #fff;
               text-shadow: 2px 2px 12px #222;
               font-size: 2.5em;
               font-weight: 700;
           }
           h2 {
               color: #8ecae6;
               font-size: 1.5em;
           }
           h3 {
               color: #ffb703;
               letter-spacing: 2px;
               font-size: 1.2em;
           }
           ul {
               background: rgba(20,20,20,0.8);
               border-radius: 8px;
               padding: 10px 20px;
               box-shadow: 0 2px 8px rgba(0,0,0,0.2);
           }
           li {
               margin-bottom: 6px;
               font-size: 1.1em;
           }
           img {
               border-radius: 12px;
               box-shadow: 0 4px 24px rgba(0,0,0,0.5);
           }
           .centered {
               text-align: center;
               color: #fff;
               background: linear-gradient(90deg, #222 60%, #333 100%);
               padding: 18px;
               border-radius: 12px;
               margin-bottom: 18px;
           }
           .large-blue-text {
               color: #219ebc;
               font-size: 2em;
               font-weight: bold;
               letter-spacing: 1px;
           }
           .larger-text {
               font-size: 1.5em;
               color: #ffb703;
           }
           form {
               background: rgba(40,40,40,0.95);
               border-radius: 10px;
               box-shadow: 0 2px 12px rgba(0,0,0,0.5);
               padding: 18px;
               margin: 18px 0;
           }
           label {
               display: block;
               margin-bottom: 10px;
               color: #8ecae6;
           }
           input, textarea {
               border: 1px solid #444;
               border-radius: 5px;
               padding: 6px 10px;
               margin-top: 4px;
               width: 90%;
               font-size: 1em;
               background: #222;
               color: #fff;
           }
           input[type="submit"] {
               background: #219ebc;
               color: #fff;
               border: none;
               cursor: pointer;
               transition: background 0.2s;
           }
           input[type="submit"]:hover {
               background: #023047;
           }
           input[type="reset"] {
               background: #ffb703;
               color: #222;
               border: none;
               cursor: pointer;
               transition: background 0.2s;
           }
           input[type="reset"]:hover {
               background: #fb5607;
               color: #fff;
           }
           .project {
               border: 3px solid #219ebc;
               margin: 8px;
               transition: transform 0.3s, box-shadow 0.3s, border-color 0.3s;
               box-shadow: 0 4px 24px rgba(0,0,0,0.5);
           }
           .project:hover {
               transform: scale(1.08) rotate(-2deg);
               border-color: #ffb703;
               box-shadow: 0 8px 32px rgba(33,158,188,0.5);
               filter: brightness(1.15) contrast(1.1);
           }
           nav {
               background: #222;
               padding: 8px 0;
               border-radius: 8px;
               margin-bottom: 12px;
           }
           nav a {
               color: #8ecae6;
               margin: 0 12px;
               text-decoration: none;
               font-weight: bold;
               transition: color 0.2s;
           }
           nav a:hover {
               color: #ffb703;
           }
           section {
               margin-bottom: 18px;
           }
           blockquote {
               border-left: 4px solid #219ebc;
               padding-left: 12px;
               color: #adb5bd;
               font-style: italic;
           }
           code, pre {
               background: #222;
               color: #ffb703;
               border-radius: 4px;
               padding: 2px 6px;
           }
           mark {
               background: #ffb703;
               color: #222;
           }
           abbr, cite, dfn, var {
               color: #8ecae6;
           }
           figure {
               background: #222;
               border-radius: 8px;
               padding: 8px;
               margin: 8px 0;
           }
           figcaption {
               color: #ffb703;
           }
           details {
               background: #222;
               color: #fff;
               border-radius: 8px;
               padding: 8px;
           }
           dialog {
               background: #222;
               color: #fff;
               border-radius: 8px;
               padding: 8px;
           }
           menu, nav ul {
               background: #222;
               border-radius: 8px;
               padding: 8px;
           }
           menu li, nav ul li {
               color: #ffb703;
           }
       </style>
   </head>
   <body>
        <div class="main-content">
           <div class="centered">
               <img src="https://placehold.co/150" alt="Placeholder graphic with neutral gray background and centered text reading 150 x 150, conveying a simple and calm tone" />
        <h1>xYoungCeejx</h1></div>
           <h2>Web developer at FreeCodeCamp</h2>
           <p>A person who thinks all the time has nothing to think about except thoughts</p>
         <div>
            <h3>I am</h3>
            <ul>
                <li>A software engineer</li>
                <li>A reader</li>
                <li>A rapper</li>
            </ul>
         </div>
         <div>
             <h3>I like to</h3>
             <ul>
                 <li>Meet new people</li>
                 <li>Learn coding</li>
                 <li>Practice penatrative testing</li>
             </ul>
         </div>
      <div>
           <h3>My Projects</h3>
           <img src="https://placehold.co/300" class="project" />
           <img src="https://placehold.co/300" class="project" />
           <img src="https://placehold.co/300" class="project" />
           <img src="https://placehold.co/300" class="project" />
        <img src="https://placehold.co/300" class="project" alt="Neutral gray background with centered text reading 300 x 300, conveying a simple and calm tone. No other elements or emotional cues present." />
      </div>
      <div>
          <h3>Links</h3>
          <ul>
            <li>
                <a href="https://github.com/xYoungCeejx">Github</a>
            </li>
            <li>
                <a href="https://x.com/xYoungceejx">X/twitter</a>
            </li>
            <li>
                <a href="https://www.linkedin.com/in/cj-stineback-b7b29b377/">Linkedin</a>
            </li>
        </ul>
    </div>
    <div>
        <form action="#">
            <label for="email" id="email">
                Email: <input id="email" placeholder="xYoungceejx@gmail.com" />
            </label>
            <label for="message">
                Message: <textarea id="message">This webpage is designed by me, through the use of HTML, and CSS</textarea>
            </label>
            <input type="submit" value="Send Message">
            <input type="reset" value="Reset Form">            
        </form>
        <section>
            <span class="large-blue-text">This text is blue and large.</span>
            <p>This is a paragraph with <strong>bold</strong> and <em>italic</em> text.</p>
            <p>This is a paragraph with a <a href="https://www.example.com">link</a>.</p>
            <p>This is a paragraph with a <code>code snippet</code>.</p>
            <p>This is a paragraph with a <span style="color: red;">red text</span>.</p>
            <p>This is a paragraph with a <mark>highlighted text</mark>.</p>
            <p>This is a paragraph with a <small>small text</small>.</p>
            <p>This is a paragraph with a <del>deleted text</del>.</p>
            <p>This is a paragraph with an <ins>inserted text</ins>.</p>
            <p>This is a paragraph with a <sub>subscript</sub> and a <sup>superscript</sup>.</p>
            <p>This is a paragraph with a <blockquote>blockquote text</blockquote>.</p>
            <p>This is a paragraph with a <pre>preformatted text</pre>.</p>
            <p>This is a paragraph with a <kbd>keyboard input</kbd>.</p>
            <p>This is a paragraph with a <samp>sample output</samp>.</p>
            <p>This is a paragraph with a <var>variable</var>.</p>
            <p>This is a paragraph with a <cite>citation</cite>.</p>
            <p>This is a paragraph with a <dfn>definition</dfn>.</p>
            <p>This is a paragraph with a <abbr title="Hypertext Markup Language">HTML</abbr> abbreviation.</p>
            <p>This is a paragraph with a <time datetime="2023-10-01">October 1, 2023</time> date.</p>
            <p>This is a paragraph with a <address>contact information</address>.</p>
            <p>This is a paragraph with a <figure><img src="https://placehold.co/150" alt="Placeholder Image"><figcaption>Placeholder Image</figcaption></figure>.</p>
            <p>This is a paragraph with a <details><summary>Details Summary</summary>
            Detailed information goes here.</details>.</p>
            <p>This is a paragraph with a <dialog open>Dialog Box</dialog>.</p
            <p>This is a paragraph with a <menu><li>Menu Item 1</li><li>Menu Item 2</li></menu>.</p>
            <p>This is a paragraph with a <nav><ul><li>Navigation Item 1</li><li>Navigation Item 2</li></ul></nav>.</p>
            <p>This is a paragraph with a <section><h2>Section Title</h2></section>.</p>
        </section>
          <section>
            <div class="centered">
                This text is centered.
                <p>HTML is awesome.</p>
            </div>
            <p>
                This text has a normal font size.
                <span class="larger-text">This text is larger.</span>
            </p>
            <!-- However, remember that font size should always be set with CSS, so you should not use this element in modern HTML. -->
          </section>
            <section>
                <header>
                    
<address>
    <h2>Company Name</h2>
    <p>
        1234 Elm Street<br />
        Springfield, IL 62704<br />
        United States
    </p>
    <p>Phone: <a href="tel:+15555555555">+1 (555) 555-5555</a></p>
    <p>Email: <a href="mailto:contact@company.com">contact@company.com</a></p>
</address>
                </header>
            </section>

    </div>     
  </body>
</html>
