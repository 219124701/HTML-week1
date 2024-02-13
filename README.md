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

- When you want to visit a website you open a web browser or a web view and enter a URL you can even type it in the adress bar and then click search result or link or open an app tht triggers it even if its that a URL is involved , the web server responds by sending back the specif HTML file lococated at the address . Back then everything that needed to be displayed in a website was contained in a single HTMLfile along with the images but things have changed the TEXT is stored in database and multiple static files are combined in real

     
    

 

                                  
 
 

 
  



                    
