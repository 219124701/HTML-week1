# INTRO HTML AND CSS
# WEEK1
# UNIT1
HTML IS A PROGRAMME THAT IS USED TO CREATE WEBPAGES , IT SERVES AS A CHANNEL FOR DIFFERENT TYPES OF CONTENT LIKE WORDS , IMAGES ect.. it also forms a solid foundation for everything in the digital realm. it has straight forwad structure with out any programming logics. it gives reselent and robustness, also can handle alot of abuse but still deliver. 
CSS : is the stylist of a web page it ia responsible of how things looks it is also fragile but powerful at the same time
if the code has a problem the browser will skip that part and move to the rest
JAVASCRIPT : it is a programming language that allows us to create intereactive staff, it can do things that html and css cannot do
it is fragile in a way that if theres an issue in the code and it does not understand the code it gives up it also refuses to run tha javaScript and will not even try to figure out the problem.


# UNIT 2
TWO QUOTES ELEMENTS WHICH IS CITE AND BLOCKQUOTES WHICH SERVE AS SEMATIC PURPOSE AND ALSO INFORMS THE COMPUTER ABOUT EVERYTHING .
THERE ARE SOME QUOTES THAT ARE NOT BLOCK QUOTES BUT THEY APPEAR WITHIN THE TEXT SOME ARE CURLY SOME ARE NOT STRAIGHT 
THERE IS ADATETIME ATTRIBUTE WHICH ALLOWS US SPECIFY DATE AND TIME IN A FORMAT THAT A COMPUTER UNDERSTAND AND IT HAS TO BE SPECIFIC. USING TIME ELEMENTS WE DO NO HAVE TO SPELL THE ENTIRE DATE ON THE WEB PAGE ALSO WEBSITES USES PHRASES . ATRRIBUTES USES PROPER MACHINE READABLE VERSION AD ALOSO PREFERD STANDARDISED FORMAT
TWO CODE ELEMENT :pre quotes and br quotes T, TO MAKE OUR CODE MORE READABLE WITH OUTWITH OUT AFFECTING WEBPAGE WHEN WE WRITE CODE WE ADD AS MANY SPACES AND LINE BREAKS AS WE WANT AND THE BROWSER WILL IGNORE THEM.
HTML SUPERSCRIPT , SUBSCRIPT AND SMALLER SCRIPT 
SUPER SCRIPT : ARE THE CHARECTERS SET ABOVE THE NORMAL BASE LINE OF THE TEXT
SUBSCRIPT : ARE THE CHARECTERS THAT ARE SET BELOW THE NORMALBASE LINE OF THE TEXT 
SMALL TEXT : ARE USED WHEN YOU NEED TO MARK UP A CERTAIN BITS OF CONTENT AS HAVING A DIFFERENT MEANING THAN THE REST

# unit3
TROUBLE SHOOTING AND DEBUGGING ON html IT CHECKS THE SYNTAX OF YOUR html CODE AND REPORTS ANY ERROR, html DEBBUGING CODE THEY USE NOTEPAD ++THAT SHOWCASES VARIOUS HTML ELEMENTS
we have atributes 1. class- it is commonly used and it assign a reusable name to any element 
                    2. id - can be used for CSS targeting , the uniqueness of an ID it ensures that there will always just one element with that ID
ARIA ROLES - it is an atribute that can be added to html elements to convey the right message about the content's meaning , it plays a role when we want to provide essential information to screen readers and magnifiers to ensure the web is fully accessible.

FORMATING HTML -it referes to the way text is displayed on a web page , comments are inserted by putting tags at the start and at the end
we use elements greater and less pre , code tags or tags with text area also if you are modifying the whitespace handling with CSS then extra spaces can matter .

# unit 4 

- Navigation and linking
 To create a link we use an A element wich is an anchor inorder to do this we need to to add href attribute that is used to  specify the URL or destination of a hyper link and this href with URL is eclosed in quotes, and the URL is the one the one that takes us to the link, URLs are versatile and when you linking to another website you can iclude the entire URL. There are types of URL which is absolute and it is called absolute becouse it a precise location on the web. 


- HTML URL PATHWAYS : in html when specifying paths for resources like images , stylesheets or links you typically encounter two pathways which is absolute path that specifies the complete URL or file path from the root . If the absolute URL were used for all links the browser will keep trying to access files, an absolute path specifies the full URL or file path from the root of the the web 
RELATIVE PATHS : 


-  TO CREATE A URL FROM SCRATCH : you need to see how files are organised and there is RELATIVE domain how to createe it ? you need to ommit the domain name but include the initial slash at the begining and this helps the browser to start from the root level of the file structure . Secondly you need to specify the path to a resource relative to the current document or lacation .
 HOW TO CREATE A LOCAL URL : creating a local URL it involves specifying the path to a resource withinyour local file system e.g if your HTML file and another file are in the same directory you can create a local link .
 

- NAVIGATION : It referes to the system or process of moving between different pages within the website . Common elements in navigation incude menus , links and buttons that guide users through the structure of the site, secondly links are wrapped in an element with the correct URL and then eclosed in a li (list) tags. to indicate the that the site is navigating  you have to encompass the menu in a nav (tags) and it needs to appear by using css styling.Breadcrumbs are a navigation aid on website showimg usesrs the path fromthe home page to the current page and are are wrapped in nav element using orderd list ol tags.
WE HAVE TWO OPRION OF WRITING URL: 1. /imgages/logo.gif - it creates a URL that is relative to the root level that means the browser will start looking for the file from the root of a website . 
                                   2. ../imges.logo.gif - creates URL that is relative to the location of the file whre the URL is written .
- ABSOLUTE AND RELATIVE URLs : when we see this URL https://www.awesomedogss.com/peaple it means that we are looking for file called index.html inside the folder called people ,. Web development when a browswer is given a URL that points to a folder it automatically looks for an index.html file and loads it , thats why it is wise to create URL structure by using folders instead of having a file named people.html.

# WEEK 2

- # UNIT 5
- HTML WORKING WITH GRAPHICS AND IMAGES

- IMAGES are almost everywhere if we want to add an image on a webpage  we use the image element which is written as IMG , we have 4 attributes thyat needs to be included on every image which are : Source attribute (SRC) which tells the broswer which image which image to load , Alte attribute (ALT) it provides text description of an image , Height and width attribute it determines the size of an object

- IMAGE FORMAT

  We have 4 main file formats : 1. GIF it is used for compressing illustrations that have large of the same colours
                                2. SVG is perfect for logos and icons
                                3. JPG is for compressing photograph
                                4. PNG it works well when you need transparency
  - RESPONSIVE IMAGES SOURCE SET FILE FORMATS
    Html allows us to deliver different image files to screens of different sizes

   -  We can create multiple image files and include them as options in our HTML code , the browser in collaboration with the OS , taks into account and devices hardware capabilities and network speed to decide which image to download
   -  when you start coding you start with the basic code for loading an image on a web       page , by using an image element with a source attribute hat points to the image file along with ALT text ,width and height .
 
   -  FIGCAPTION - The < figcaption > element is used to provide a caption for  '< FIGURE >' element , typically used with images or illusrations .
 
# unit 6 
- WORKING WITH MEDIA

- working with media in html typically involves embedding audio,video, and images into web pages
- Various types of media

1. Images : uses the '<img>' tag to display images. you need to to specify the 'src'attribute with the URL of the image file . for example
   <img sc="image.jpg" alt = "Description of the image" >
2. Audio : Use the '<audio'> tag to embedd audio files. You can specify multiple source files to provide compatibility with different browsers e.g
< audio controls>
<source src= "audio mp3" type ="audio/mpeg">
</audio>

3. VIDEO : Use the '<video>' tag to embedd video files . Similar to audio , you can specify multiple source files e.g
<video contols >
<source src= "video mp4" type =" video/mp4" >
</video>

4. Embedding from External Source : You can also embed media from external sources like youtube or Vimeo using their provided embed code. e.g
   <iframe width ="560" height ="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder= "0" allowfullscreen></iframe>iframe>
   It is important to always provide the alternative text ('alt'attribute ) for images and a fallback message for audio and video elements incase the browser doesnt support then or the media fails to load .


   # unit 7
   HTML CONTENT IDENTIFICATION

   HTML LANGUAGE SUPPORT

   - People speak various languages but in HTML there are tools to indicate the language of your content . By setting things up correctly , search engines will understand which language of your content .
   - Theres a lang attribute that is used to specify the language of a webpage . if the wthe whole page is is in one language then it is quite simple becouse you set the language on the main element that wraps everything else whch is usually the HTML element .
   - for example <"en-US" in the lang attribute it means U.S english , and we can also use "en-GB" for english in great Britain . it is also important to specify the content's direction becoase almost all the languages flow from left to right horizontally but some from right to left. Use the dirattribute to indicate the dirction and it once on the outer HTML.
  
<html lang="en-US">
<html lang="en-gb" dr="ltr"
<html lang="ar" dir="rtl">
<meta charset="UTF-8">

HTML Generic Elements , dive and Span
-in html , '<div' and '<span>' are both elements used for styling and structuring content but they serve different purpose : 
1. '<div>' short for division is a block element used to group together related content and apply styles to the entire block and it is commonly used for creating sections of a webpage such as geaders , footers,sidebars
2. '<span>' is an inline level element used to apply styles to a specific part of the content usually within a larger block of text .but it does not create any line breaks and only takes up as much width as its content requires . it is also used for stling like color , font size or formatingto small portions of text within a paragraph or inline elements.

WORKING WITH DIV AND SPAN ELEMENTS 
When working on css layout you are required to group these paragraphs together. The purpose is to add a background color only to the paragraphs , to do this well we have to introduce a Div with a class called boxes an example if there is a phrase in the middle of the text tha needs to be specifically targeted for some reason and it is written in Spanish we have to change its language attribute to reflect that by using inline element span to mark the desired phrase .  both div and span can make use of varipus global attributes like class,id,lang and aria roles.

# UNIT 8
HTML INTERGRATION

- When you want to visit a website you open a web browser or a web view and enter a URL you can even type it in the adress bar and then click search result or link or open an app tht triggers it even if its that a URL is involved , the web server responds by sending back the specif HTML file located at the address . Back then everything that needed to be displayed in a website was contained in a single HTMLfile along with the images but things have changed the TEXT is stored in database and multiple static files are combined in real.

- HOW TO STRUCTURE THE WHOLE HTML FILE
- The file should begin with a doctype statement which indicates the era of this html file.
- enclose everything else on the page within an html element wich named HTML, it tells us that all the content within it is html , place the opening html tag at the top and the closing html tag at the bottom. also declare the language being used and the content flow direction

- IN HTML we have two parts which is head and the body
- HEAD : it contains all the metadata that the browser needs to know but will not display on the page
- BODY : is for all the content and is composed of various elements whereby most of the action happens.
- The doctype declaration , html head and body elements are the essential building blocks of every web page.

DOCUMENT HEAD
- on the head of the website you only put important information that the browser needs to know about the website . The charecter needs to be seen by the browser and you have to use meta element , and make sure that elements are only placed inside the head as they provide metadata about the page. To define the charecter set use the charecter set attribute and set it to UTF-8.

  The Meta Tag
  - it is used to inform the browser that the layout has been adjusted to fit small screens , making it a responsive website. without the meta tag the browser assumes the page follows an order layout technique designed for destops which needs to be scaled for mobile devices, it is also useful to include a description of the site which appears in search engine.
 
  - THE LINK ELEMENT
The link element is an important component used extensily within the head section it serves to connect various assets that should load such as CSS files ,font and favicons. To inform the browser about the type of asset you have to utilize the rel attribute.
- the href attribute is employed to specify the URL asset. e.g a link to a style sheet would appear like this , indicating the rel attribute as stylesheet. you can also include a link to s in the order they are listed . preload a font file , it is important to consider that the browser will load the file , it is advisable to to place the items that need to load first at the top while less delayed use items can be positioned further down. SCRIPT ELEMENT
 <script src=" my-javascript-file.js"> </script>
- Script tag is a commonly used element in html document's head it instruct the browser to load a javascript file even though it s placed at the end of the document.

- 6 IMPORTANT ELEMENTS WHEN STRUCTURING THE CONTENT
  1. MAIN ELEMENT it is uesd once per webpage and tells the browser where the main content is located.
  2. HEADER is uesd for site headers ,articlesheaders, and headers within the content . A header is usually found at the top of most web pages and may include a logo adn navigation.
  3. FOOTER it signifies that there are extra things to convey regarless of its position on the page.
  4. ARTICLE - it starts with a title , subtitle , authors name and publicatin date which can be considered as a header. Some articles begin with metadata like hashtags or share buttons which is suitable for a footer element.
  5. SECTION ELEMENT : Is used to mark sections for content e.g in a long essay with subheadings each segment can be wrapped in a section element and it is also used for dividing different topics zones on a website.
  6. ASIDE is an element that is used for content that is off to the side like sidebar information or additional details that accompany an article, Aso an advertising can be an aside.

     # UNIT 9
     WORKING WITH FORMS AND INTERACTIVE ELEMENTS

     - Form fields have been an essential part of the web for a long time and it is used for various tasks like ligging into websites , making purchases, conducting searches and also adding content. It is very wise to use semantic form elements in HTML instead of divs and Spans because it allows us to leverage the built in power of the browser. Using html form elements we ensure that the forms will be compatible with all devices and input output hardware .
     - When creating a form to sgn up for an email newsletter we use two fields wich is THE PERSON'S NAME  and their EMAIL ADRESS.
     - When creating a form we start with the form element that informs the browser about the presence of a form using opening and closing tags , there is a newsletter signup form that also needs two fields which is name and email that can be turned into labels using the lebel element.
     - we use the input element to provide for users to input their name and email unlike other elements , the input element does not have a closing tag due to its older structure and it actd as a maker for the browser to bring in functionality and place it there.
     - the a Button is needed for users to submit the form , when the form lacks functionality it needs to be connected to the backend then add an action and method attribute to make a demo work .
     - after you done setting up land on the response page but if the data that was entered does not appear this is becouse the input fields need a "name" attribute to report the data.
     - To make it accessible to everyone we need to adress the issue of the label and input elements not being connected w, we have two options to figure this out
       1. add a "for" attribute to the label that matches the "id" attribute of the input .
       2. Wrap the input with the label .

          FORM FUNCTIONS
      - The purpose of creating the is to collect a name and email adress in order for people to sihn up for an email nwesletter. Thhe below links shows how to ceate a form:

![image](https://github.com/219124701/HTML-week1/assets/158051727/3a19b264-c920-484a-91ce-e6d2883254b5)

- When people want to fill out this form the browser wi;; verify that the data that was entered is an email and when a user tries to type anything other that than an email address they will get a warning and asked to fix it , also the purpose is to tell the browser that our button is a submit button if it happens that there are many buttons we inform the browser which button to activate when a user hits return on their keyboard , required attribute can also be added to make the the email feel required
- HYML can put a placeholder in the form , use the placeholder attribute and put a suggestion . Then sugested text should appear light gray by default and as soon as this field is clicked the placeholder text disappears , this proves that the user dhould not erase tis placeholder text in order to write their own email address .

- The forms does not have to be ugly , we use css to style forms to render muc better than simple text boxes , Proper semantic html elements can be used in forms to style them . 
     
    
![image](https://github.com/219124701/HTML-week1/assets/158051727/c0a57429-9ff6-4ed9-945f-f695683763e8)
the above link is a form structure whereby theres an email and name along with a button just with better styling . add three more fields : password , search and phone number to see what they can do 
- These are are very similar in structure to the text and email from fields, for the password field the type the equals password. When we start to type into the password field the browser will warn us not to set up to use HTTP and not HTTPS which is good, users should not fill out the forms like this on sites that have not been secured by HTTPS.

  # UNIT 10
  ORGANISING TABULAR INFORMATION IN HTML.

  HTML TABLES
  html tables are used for tabular data , A bunch of information that is best communicated by aligning things into rows and columns it is a data table.
  - How to decide to use a table in html because there is speific information that is best conveyed in a table : you compare prices of things that are for sale , population data by town ,election results, product comparisons , schedule, bits of information collected that people want to quickly compare. You can use CSS to rearrange how a table have to look like , what is important is inherently a table then use an html table.
 
    BUILDING HTML TABLES
    to create an html table we can simple use several different HTML elements in just the right combination . table ,table row(TR) , table header (TH) , Table header (TH). The table element wraps around the whole table , around all our content and markup for that table, marking the begining and end of the table its self. TR stands for table raw that wraps around a set of elements , defining them as elonging to the same row . The TH stands for table header that defines a header for a column then TD stands for table data and marks up the cells of dats.

    INTRODUCTION TO CSS

    # UNIT 1

    css is a style sheet language. ccs have two components which is Property and the Value
    -How to write a comment and an Element Selector : when you writing your first element selector you open it and find a set of headings , subheadings and paragraphs that we can work with.
    - SELECTORS in css , if we want to select all the paragraphs on our page and make them any color of my choice we can use the html element P as the selector.
    - then in our CSS we write "P" without the angle bracket and set the color property to blue .
    - Then if it happens that i want to change all Headings Red we uae selector "H2" in the css also use the color property and set it to red .that will make the page Red.

    HOW TO WRITE A CLASS SELECTOR.
    A class is an attrribute that can be added to an HTML,it provides an additional details about that element .

  - First you have to start with html code . if we want the first paragraph tag and give it a name like "intro". this way it will stand out as an the introductory paragraph .
  - in CSS we use dot (.) before any class name to differentiate it from HTML element selectors Write ".intro" and set the color to green.
  - If we want to style a specific part of a paragraph differently we can use Span element with a class attribute e.g you have to make the sentence about tha guarantee orange and bold. how to do this? by adding the span tag with class="guarantee"around that sentence in the HTML. Then, in ccs we write ".guarantee" to select the class and set the color to orange and the font-weight to bold.
 
TAKE THE SENENCE "PHILANTROPHY IS EXTREMELY IMPOETANT TO US" AND MAKE IT BLACK ,BOLD AND ALL UPPERCASE . A STARTING POINT HAS ALREADY BEEN PROVIDED TO YOU WITH THE SETTING OF THE CLASS NAME AS"IMPORTANT" AND THE CSS PROPERTY "TEXT-TRANSFORM:UPPERCASE". FIND A WAY TO SELECT THAT SENTENCE IN THE HTML AND COMPLETE THE STYLE BY MAKING IT BLACK AND BOLD: ANSWER BELOW
 
   .important {
  color: black; /* Set the text color to black */
  font-weight: bold; /* Make the text bold */
  text-transform: uppercase; /* Transform the text to uppercase */
}

YOU CAN INCLUDE THIS CSS IN A STYLE TAG WITHIN THE <HEADS> SECTION OF YOUR HTML DOCUMENT OR EXTERNAL CSS FILE LINKED TO YOUR DOCUMENT , HERE'S IS HOW YOU WOULD LIKE TO USE IT IN YOR HTML:

<!DOCTYPE html>
<html>
<head>
  <style>
    .important {
      color: black;
      font-weight: bold;
      text-transform: uppercase;
    }
  </style>
</head>
<body>
  <p class="important">Philanthropy is extremely important to use</p>
</body>
</html>

GROUPIG SELECTORS
 - its a selector that allows us to apply multiple selectors at once by separating each selector with a comma e.g

.class 1, .class 2, .class 3{
color: blue,
}
 DESCENDANT SELECTOR 
 - it is used to select elements that are descendant element of a certain element , it can be nested at any level within the ancestor element e.g

div p {
backgroug: blue,
}

# unit 3 
IDENNTIFY A COLOR SCHEME

The most common way to represent color online is through hex codes that is also knwn as hex values or hex format 
- Hex values are typicall six digits long and consists of numbers from zero to nine and letters A to F. The first two digits represent red, the next two represent green and the final two represent blue . These digits correspond to number ranging from zero to 25.

BACKGROUND AND TEXT COLOR IN CSS 

-To find a color we like , refer to the named color chart provided in the exercise fies, scroll down and chose a teal color by changing to pink teal , we can also select a color palette  called "Fiery Cracked Earth" in canva which includes the colors you may want to use . it is important to note that canva assigns names to these colors, but they may not work in sublime text instead work with the hex valuesp provided on CSS and named colors chart.


n CSS, text colors are set using the color property. This property specifies the color of the text content within an element. It's crucial to ensure good contrast between the text color and the background color to improve readability, especially for users with vision problems. High contrast is recommended to make the text easily distinguishable from the background 14.

To set the text color in CSS, you can use color names, hexadecimal color codes, RGB values, or HSL values. Here are some examples:

Using color names supported by all browsers, such as Red, Blue, Green, etc. 3.
Using hexadecimal color codes, e.g., #FF0000 for red, #0000FF for blue, #008000 for green 3.
Using RGB values, e.g., rgb(255, 0, 0) for red, rgb(0, 0, 255) for blue, rgb(0, 128, 0) for green.
Using HSL values, e.g., hsl(0, 100%, 50%) for red, hsl(240, 100%, 50%) for blue, hsl(120, 100%, 50%) for green.

AN EXAMPLE OF SETTING A TEXT COLOR:
p {
    color: #333; /* Hexadecimal color code for dark gray */
}

It's also important to consider the contrast between text and background colors to ensure your text is easily readable. For instance, a text color of #333 (dark gray) with a background color of #f2f2f2 (light gray) provides good contrast, making the text easily readable:


Background text colors in CSS can be set using the background-color property. This property allows you to specify the background color of an element, which can be any HTML element like a paragraph (<p>), heading (<h1>, <h2>, etc.), div (<div>), span (<span>), and more. The background-color property can accept various types of color values, including color names, hexadecimal color codes, RGB values, and HSL values, similar to the color property for text colors.

Here are some examples of setting the background color using different methods:

Color Names: You can use color names supported by all browsers, such as Aqua, Beige, Black, Blue, Cyan, Gold, Gray, Fuchsia, etc. 1.

Hexadecimal Color Codes: For example, #F0F8FF for light blue, #00FFFF for cyan, #F5F5DC for beige, #000000 for black, #0000FF for blue, #F5F5DC for beige, etc. 1.

RGB Values: For instance, rgb(153, 102, 153) for a specific shade of purple, rgb(255, 255, 204) for a light yellow, etc. 4.

HSL Values: For example, hsl(240, 100%, 50%) for blue, hsl(120, 100%, 50%) for green, etc. 4.


Here's a simple CSS example that sets the background color of a paragraph element:
      p {
    background-color: #F0F8FF; /* Light blue */
}


And another example using an RGB value for a div element:
div {
    background-color: rgb(153,  102,  153); /* Purple */
}

 important to ensure that the background color provides sufficient contrast with the text color to maintain readability. Tools like the WebAIM Contrast Checker can help you determine if the contrast ratio between your text and background colors meets accessibility standards, aiming for a minimum contrast ratio of 4.5:1 for normal text and 3:1 for large text 2.

For more complex scenarios, such as applying a background color only to a portion of the text within an element, you can use a <span> element inside the text block and apply the background-color property to the <span> instead of the entire block. This method allows for more granular control over the styling of specific parts of the text:

<h1><span style="background-color: yellow;">Highlighted Text</span></h1>


n this example, only the "Highlighted Text" portion of the heading will have a yellow background, while the rest of the heading remains unchanged.
                    
