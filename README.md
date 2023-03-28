# Recipe Project README
## Purpose
The purpose of this project was to cover the foundational concepts of HTML and integrate them by creating a simple recipe webpage that provides links to other pages within the site. The index.html serves as the homepage for the website and follows an important naming convention that allows this to be the default page when looked for by a web server. HTML can be used to generate the structure of a webpage through elements that consist of tags, attributes, and content within the tags; where the term markup language in the name derives from. A browser parses through these HTML files and displays the content based on what tags where used and what content is within them. Explored in this project are many of the basic tags such as:
<ul>
  <li> &lt;HTML>which denotes the document type </li>
  <li>&lt;Body> and &lt;Head> which provide the content of the page and additional meta information about the document respectively</li>
  <li>&lt;p> which is used to create paragraphs within a series of characters</li>
  <li>&lt;em> and &lt;strong> which are used to stylize the text with italic and bold emphasis</li>
<li>Finally, &lt;ul>, &lt;ol> and &lt;li> can be used to present lists, both ordered and unordered</li>
</ul>
Additionally, topics regarding the linking process were also explored, with particular distinction between absolute and relative links. Relative links were used in the project to point to the proper image files in the file system in order to display in the page and are in general used to navigate to other pages within a website. This example shows navigation to the parent directory followed by the proper folders to find the desired image. <br>
<br>
`&ltimg src="../images/dog.jpg">`
Absolute links can be used to link to other external pages that are not a part of the website and require explicit syntax such a protocol used, domain name, and resource path in order to link properly.
<br>
<br>
```HTML
<span style="color:blue">https://</span><span style="color:orange">www.microsoft.com</span><span style="color:green">/en-us/microsoft-365</span>
```
