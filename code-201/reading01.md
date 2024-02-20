# Getting Started

## How the Web Works
#### 1. Compose a short poem describing how HTTP sends data between computers.
- Here goes nothing:
    * Within packets across the web they soar,
HTTP seeks and receives data evermore.
Through cyberspace they travel and flow,
And now, a webpage to show.



#### 2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
- The browser parses the HTML file first which allows the browswer to identify any linked elements that may be on an external CSS stylesheet.
- As the browser parses the HTML, it requests back to the server for any CSS files found from *link* elements, and any JavaScript files that has been found from *script* elements. From those, the browser then parses the CSS and JavaScript.


#### 3. How can you find images to add to a Website?
- You can easily search through Google Images for an image. 
- **Note**: most images on the internet, including Google Images, are copyrighted. To minimize the liklihood of violating a copyright, use Google's license filter. 
- **How To**:
    - Click on the *Tools* button.
    - Click *Usage rights*.
    - Choose the option *Creative Commons licenses*.
        


#### 4. How do you create a String vs a Number in JavaScript?
- String: you enclose text within singe quotes (' ') OR double quotes (" ").
- Number: you simply write out the digits: 
let thisNumber = 10; 
    


#### 5. What is a Variable and why are they important in JavaScript?
- Variables are containers that store values. A user begins by declaring a variable with the 'let' keyword, followed by the chosen name for said variable.
- Variables are necessary in order to do anything interesting in programming. If values couldn't change, then developers couldn't do anything dynamic; like personalize a greeting message.
- See: [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)



## Introduction to HTML
#### 1. What is an HTML attribute?
- Attributes contain extra information about an HTML element that will not appear in the rendered content.
- An attribute should have:
    * A space between it and the element name.
    * The attribute name, followed by an equal sign.
    * An attribute value, wrapped with opening and closing quote marks.



#### 2. Describe the Anatomy of an HTMl element.
- The opening tag: Consists of the element name. This tag marks where the element begins to take effect.
The content: This contains the content of the element.
The closing tag: This is the same as the opening tag, exept that this tag includes a forward slash before the element name. This indicated where the element ends. Failing to close tags is often a commone beginner mistake.


#### 3. What is the Difference between *article* and *section* element tags?
- Article tags enclose a block of related content that makes sense on its own without the rest of the page.
- Section tags are similar to article tags, but it is used more for grouping together a single part of the page that constitues one single piece of functionality (i.e. a mini map or set of article headlines and summaries), or a theme. 


#### 4. What Elements does a “typical” website include?
- Header: usually sits across the top with a big heading and/or logo.
- Navigation bar: links to other parts of the website.
- Main content: houses the main material for the page (i.e. the video that a user came to watch, the article that popped up in Google, etc.)
- Sidebar: periperhal content such as related articles, links to partner websites, advertisements, etc.
- Footer: sits across the bottom and usually contains links to legal information, displays the copyright logo, has other links such as 'Contact Us', 'About Us', 'Privacy Policy". Normally, the information listed down here is considered secondary to the website itself.


#### 5. How does metadata influence Search Engine Optimization?
- "Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines." - [What's in the Head? Metadata in HTML.](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML#active_learning_the_descriptions_use_in_search_engines)


#### 6. How is the <meta> HTML tag used when specifying metadata?
- It is nested within the *head* element of an HTML document.



## Miscellaneous
1. What is the first step to designing a Website?
    - Answer these first few questios before doing anything else:
        * What exactly do I want to accomplish?
        * How Will a website help me reach my goals?
        * What needs to be done, and in what order, to reach my goals?
2. What is the most important question to answer when designing a Website?
    - What exactly do I want to accomplish?



## Semantics
1. Why should you use an *h1** element over a *span* element to display a top level heading?
- "This will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job."
    * See: [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

2. What are the benefits of using semantic tags in our HTML?
- Screen readers can use it as a signpost to help visually impaired users navigate the page.
- Suggests to the developer the type of data that will be populated.
- Semantic namnig mirrors proper sutomer element/component naming.


## What is JavaScript
1. Describe 2 things that require JavaScript in the Browser?
- Browser APIs and Third Party APIs

2. How can you add JavaScript to an HTML document?
- Internal
- External
- Inline

