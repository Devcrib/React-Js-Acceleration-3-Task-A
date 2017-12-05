React-Js-Acceleration-3-Task-A


Wait, There is an HTML5 ?
Yes. yes there is. :). 
I know..I know, it’s pretty old news..but that doesn’t stop me from talking about.
Because I’m Batman!. 
Lol, just kidding…( Shoutout to the hishe fans btw).
The biggest advantage that HTML5 has over its unnumbered predecessor is that it has high-level audio and video support which was not a part of the version specifications in previous HTMLs. Other differences between HTML and HTML5:
· The former doesn’t allow JavaScript to run within the web browser (it instead runs in the browser interface thread) whereas the latter provides full support for JavaScript to run in the background (This is possible courtesy to the JS web worker API of HTML5).
· Introduction of new tags such; summary, time, aside, audio, command, data, datalist, details, embed, wbr, figcaption, figure, footer, header, article, hgroup, bdi, canvas, keygen, mark, meter, nav, output, progress, rp, rt, ruby, section, source, track, video.
· SVG, canvas and other virtual vector graphics are supported in HTML5, whereas in HTML, using vector graphics was only possible by using it in conjunction with different technologies like Flash, VML, and Silver-light, etc.
· HTML5 uses web SQL databases, application cache for temporary storing data, meanwhile, in HTML, only browser cache could be utilized for this purpose.
· In HTML5, inline MathML and SVG can be used in text whereas this wasn’t possible in HTML.
· The flow/structure on how the new tags/elements operates is illustrated as below:
EXAMPLES
Some awesome HTML5 examples and code snippets.
1) Hidden: HTML5 introduce the hidden attribute, which allow you to hide a specific element Specifies that an element is not yet, or is no longer, relevant, as you would do it in CSS using display:none.
<p hidden>You can't see this text</p>


2) Contexmenu: Specifies a context menu for an element. The context menu appears when a user right-clicks on the element
<section contextmenu="mymenu">


<p>Yes, this section right here</p>


</section>






<menu type="context" id="mymenu">


<menuitem label="Please do not steal our images" icon="img/forbidden.png"></menuitem>


<menu label="Social Networks">


<menuitem label="Share on Facebook" onclick="window.location.href = 'http://facebook.com/sharer/sharer.php?u=' + window.location.href;">   </menuitem>


</menu>


</menu>


3) Url and email input types: HTML5 introduced new input types url and email are one of those. They allow you to write a more semantically correct code and make the form completion easier on mobile devices, by displaying special buttons (like the @ or .com buttons) depending on the input type.
Here is the url attribute in action:
<input type="url" value="">


And the email attribute as well. Please also pay attention to the pattern attribute as I will explain it below.
<input type="email" pattern="[^ @]*@[^ @]*" value="">


4) Regexp patterns for form validation: Before HTML5, when you used a form on your website, you had to use JavaScript to create a front-side validation. Now with HTML5 and the pattern attribute, you can define a regular expression pattern to validate the data.
The following snippet is for validating email addresses:
<input type="text" title="email" required pattern="[^@]+@[^@]+\.[a-zA-Z]{2,6}" />


This one is for strong passwords:
<input title="at least eight symbols containing at least one number, one lower, and one upper letter


KEY ADVANTAGES PROVIDED BY HTML5 FOR DEVELOPERS
HTML5 wanted developers to have more flexibility while designing websites and there have been significant improvements that are worth noticing:
1. Mobile web made Easier: Even today, creating a mobile version of a website can be a headache for developers. The smartphone-owning demographic has seen exponential proliferation over the past decade, and that created a need for improved HTML standards. End users want to be able to access a web resource at any time and via any device which makes having responsive websites a requirement. HTML5 has made mobile support a lot simpler by being able to cater to the low-powered electronic devices like tablets and smartphones
2. Persistent error handling: Most of the browsers have the support to parse structurally/syntactically incorrect HTML code, but until a few years ago, there was no standardized process to handle this. It meant that new browser developers had to perform malformed HTML document tests in different browsers in the bid to create improved error handling processes via the marvels of reverse engineering
3. Enhanced support for web application features: One of the primary goals of HTML5 was to allow browsers to function as application platforms. Web sites in the past used to be a lot less complex but over time, the cumbersomeness has increased. HTML5 provides developers with enhanced control of their websites’ performance. In the past, the developers had to use workarounds because many server-side technologies and browser extensions were not present.
4. Improved semantics for elements: To enhance code insinuation, improvements have been made to the semantic roles of various existing elements. Section, article, nav and header are the new elements that have replaced most of the now-obsolete div elements, and this has made the process of mistake-scanning a whole lot less complicated.


REFERENCES
· https://www.hostinger.com/tutorials/difference-between-html-and-html5
· https://www.catswhocode.com/blog/html5-code-snippets-to-take-your-website-to-the-next-level
· www.w3schools.com/tags/default.html