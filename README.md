# HTML Essential Training
- It stands for the HyperText Markup Languages
- It defines the content of the sites
- Simple syntax `<p>` - stands for paragraph
- Basic Struture</br>
![alt text](https://github.com/brianblaze14/html-essential-training/blob/master/images/HTML-Basic-Structure.PNG)
- Each tags are called elements

## DOM Tree (Document Object Model)

- The hierarchy and structure of the html elements, often used for targeting elements in CSS and JavaScript
- URL for immediate html coding and testing (https://codepen.io/pen/)

## HTML Attributes

1. Paragraphs element, `<p>Content.........</p>` example:https://github.com/brianblaze14/html-essential-training/blob/master/html/01_basic_syntax.htm

2. Headlines element,  `<h1>Content.........</h1>` -> There are six headline tags `<h1>,<h2>,<h3>,<h4>,<h5>,<h6>` -> `<h1>` is the biggest Example:https://github.com/brianblaze14/html-essential-training/blob/master/html/01_basic_syntax.htm

3. Bold or Italics element, </br>
&nbsp;&nbsp;&nbsp;&nbsp; a) `<i>` for Visual-only Italics</br>
&nbsp;&nbsp;&nbsp;&nbsp; b) `<em>` Emphasis Italics</br>
&nbsp;&nbsp;&nbsp;&nbsp; c) `<strong>` Importance, seriousness and urgency</br>
&nbsp;&nbsp;&nbsp;&nbsp; d) `<b>` just bold example: https://github.com/brianblaze14/html-essential-training/blob/master/html/01_basic_syntax.htm</br>

4. Lists element,

&nbsp;&nbsp;&nbsp;&nbsp; a) Unordered lists `<ul>` stands for list items -> Bulleting will occur https://github.com/brianblaze14/html-essential-training/blob/master/html/02_list.htm </br>
&nbsp;&nbsp;&nbsp;&nbsp; b) Ordered Lists `<ol>` stands for list items -> Numbering will occur https://github.com/brianblaze14/html-essential-training/blob/master/html/02_list.htm </br>
&nbsp;&nbsp;&nbsp;&nbsp; c) Definition Lists `<dl>` example: https://github.com/brianblaze14/html-essential-training/blob/master/html/03_definition_list.htm

5. Date & Time element, example: https://github.com/brianblaze14/html-essential-training/blob/master/html/04_date_time.htm

6. Quotes element, </br>
&nbsp;&nbsp;&nbsp;&nbsp; a) Inline Level element eg: `<q>`</br>
&nbsp;&nbsp;&nbsp;&nbsp; b) Block Level elements eg: `<blockquote>`</br>
&nbsp;&nbsp;&nbsp;&nbsp; c) Syntax example: https://github.com/brianblaze14/html-essential-training/blob/master/html/05_quotes.htm

7. Code pre br element, example: https://github.com/brianblaze14/html-essential-training/blob/master/html/06_code.htm

8. Math Subscripts Superscripts element, example: https://github.com/brianblaze14/html-essential-training/blob/master/html/07_subscripts_small_texts.htm

9. Article element, example:  https://github.com/brianblaze14/html-essential-training/blob/master/html/08_supporting_languages.htm

10. Link element, example: https://github.com/brianblaze14/html-essential-training/tree/master/html/links

11. Nav element, example: https://github.com/brianblaze14/html-essential-training/blob/master/html/navigation/01_nav.htm

12. Breadcrumb element, example: https://github.com/brianblaze14/html-essential-training/blob/master/html/navigation/02_breadcrumbs.htm

13. Images and graphics: img srcset figure and figcaption elements, example: https://github.com/brianblaze14/html-essential-training/tree/master/html/images_%26_graphics

14. Global attribite, aria roles, formatting, &character, example: https://github.com/brianblaze14/html-essential-training/tree/master/html/power_of_html

15. Audio element, example: https://github.com/brianblaze14/html-essential-training/tree/master/html/audio

16. Video attributes, example: https://github.com/brianblaze14/html-essential-training/tree/master/html/video

17. Supporting languages </br>
&nbsp;&nbsp;&nbsp; lang element -> lang="en-US" American English, lang="en-GB" Brittan English, "color" vs. "colour" usage </br>
&nbsp;&nbsp;&nbsp;&nbsp; lang attributes -> Langauage, Script, Attributes </br>
&nbsp;&nbsp;&nbsp;&nbsp; example: https://github.com/brianblaze14/html-essential-training/blob/master/html/08_supporting_languages.htm

18. Generic elements div and span, example: https://github.com/brianblaze14/html-essential-training/blob/master/html/09_generic_elements.htm

## HTML Page development

- A Web consist of the following flows:</br>
&nbsp;&nbsp;&nbsp; a) URL</br>
&nbsp;&nbsp;&nbsp; b) Request </br>
&nbsp;&nbsp;&nbsp; c) HTML file with extension .htm or .html </br>

- HTML file - The first file that's returned in response to a request for a webpage and is headquatered </br>
&nbsp;&nbsp;&nbsp; a) The doctype declaration - Declares which era this HTML file is from </br>
&nbsp;&nbsp;&nbsp; b) The head element - Contains information the browser needs to know, though it won't be displayed </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1) The meta element: </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Only used inside the head element </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Conveys metadata about the page </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Synatax: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Synatax: `<meta name="description" content="A description that this site will show up in search engine results">`</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![alt text](https://github.com/brianblaze14/html-essential-training/blob/master/images/Meta_data.PNG)</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2) The link element: </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - It links to a range of other assets we want to load i.e css, fonts etc </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3) The rel element: </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Tells the browser  whcih kind of asset it is </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - href is used to provide the URL to the asset </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ![alt text](https://github.com/brianblaze14/html-essential-training/blob/master/images/links.PNG)</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3) The script element: </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Tells to load a javascript file </br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - General syntax `<script src="my-script.js"></script>` </br>
&nbsp;&nbsp;&nbsp; c) The body element - Contains the information and content that will be displayed on the page</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1) main - wraps around the main content of the page</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2) header - Used to mark the page where content is header</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3) footer - Used to mark the page where content is footer</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4) article - araped around any instance of an article</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5) section - wrap around the sections of contents</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 6) aside - Marks content that is off to the side or not the main attraction

- Form basics, example: https://github.com/brianblaze14/html-essential-training/blob/master/html_page/01_form_element.htm
- Different types of form basic elements, examples: https://github.com/brianblaze14/html-essential-training/blob/master/html_page/02_more_on_form.htm
- Tables basics, example: `<table>`,`<tr>`, `<th>`, `<td>`, example: https://github.com/brianblaze14/html-essential-training/blob/master/html_page/03_table.htm
 

## Websites to refer for the Web development: Specifications, Web Standards HTML 5
- https://developer.mozilla.org/en-US/
- https://html.spec.whatwg.org/
- https://html.spec.whatwg.org/dev/#toc-semantics - dev version
- https://www.w3.org/WAI/standards-guidelines/wcag/ - web accessibility reference
