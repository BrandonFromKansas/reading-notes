THIS IS AN IMPORTANT TOPIC TO COVER BECAUSE...


# Introduction to HTML (continuted)
[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
### 1. Why is it important to use semantic elements in our HTML?
- Semantic elements are used to give structure to a web page.
- Developers need to ensure they are using the correct elements, giving the content its correct meaning, function, or apperance.
- For example: the <*h1*> element is also a semantic element, which give the text that it encompases the meaning of "top level heading on this page."

### 2. How many levels of headings are there in HTML?
- There are six total.
- h1, h2, h3, h4, h5, h6


### 3. What are some uses for the *sup* and *sub* elements?
- Sup (short for *superscript*)
- Sub (short for *subscript*)
- These need to be used when marking up items like dates, chemical formulae, and mathematical equations so they are given the correct meaning. 
- See: [Superscript and Subscript](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)

### 4. When using the *abbr* element, what attribute must be added to provide the full expansion of the term?
- The *abbr* is used to wrap around an abbreviation OR an acronym.
- For either one of these instances:
    * Be sure to provide a full expansion of the term in plain text on first use, along with the <*abbr*> to mark up the abbreviation or acronym.


# Learn CSS
### 1. What are ways we can apply CSS to our HTML?
- 1 - External sylesheets. This is a separate file with a .css extension. It is the most commond and useful way to apply CSS to a document. A single CSS file can be linked to multiple web pages.

- 2 - Internal stylesheets. These are contained **within** an HTML document. To achieve this, the developer places CSS inside of a <*style*> element contained inside the HTML <*head*>.

- 3 - Inline styles. These affect a single HTML element, contained within a *style* attribute

### 2. Why should we avoid using inline styles?
- It is actually considered NOT a best practice.
- It is the least efficient way to implement CSS when it comes to maintenance. One single styling change may require multiple edits within a single page.
- Inline styling mixes CSS (presentational code) with HTML and content, this makes everything more difficult to read, decipher and understand.

### 3. Review the block of code below and answer the following questions:
- What is representing the selector?
    * **h2**

- Which components are the CSS declarations?
    * **color** and **padding**

- Which components are considered properties?
    * **black** and **5px**


# Learn JavaScript
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
### 1. What data type is a sequence of text enclosed in single quote marks?
- Single quote marks ( **'** ) turn *numbers* into *strings*
![Single Quote Marks](./assets/Single%20quote%20-%20numbers%20vs%20strings.png)


### 2. List 4 types of JavaScript operators.
- 1. Strict equality ( === )
This performs a test to see if two values are equal and of the **same** data **type**. It will return a true/false (Boolean) result.
- 2. Assignment ( = )
This will assign a value to a variable.
Example: let myVariable = 'Bobbi'; 
- 3. Addition ( + )
Add two **numbers** together or combine two **strings**.
![Addition Operator](./assets/JavaScript%20Operator%20-%20Addition.png)

- 4. Subtraction ( - ), Multiplication ( * ), Division ( / ).


### 3. Describe a real world Problem you could solve with a Function.
- Picking up after my dogs in the backyard. For every piece of "mess", place into plastic bag. Then, take plastic bag to dumpster and dispose.