#Introduction to HTML & CSS


##HTML
###what is HTML?
HTML stands for **Hyper Text Mark Up Language**
HTML provided the content you see on websites (ie text, images & links)
HTML is not used to provide style (colour, sizing etc), but the the wording and key images.
Links to other pages (on your site or others) are created in the HTML

###Some Basic HTML
```
<!DOCTYPE html>
  <html>
    <head>
      <title>Page Title</title>
    </head>
    <body>
  
      <h1>My First Heading</h1>
      <p>My first paragraph.</p>
  </body>
</html>
```

HTML is made up of tags, ie `<html> </html>`, almost all html tags are pairs, with an opening tag `<p>` and a closing tag `<p>`.

Tags that are contained inside other tags, for example;
```
<body>
  <h1> heading inside body tags </h1>
</body>
```
are know as **nested tags** and are also know as **children** of the outer tags. The outer tags are known as **parents**. You will hear these terms used alot.

##Creating your first HTML page

1. First create a new folder (directory) on your computer
2. Open it using your text editor (ie Sublime, atom, etc)
3. Create a new file from your text editor and save it as **index.html**
4. Add a basic html outline (including `<!DOCTYPE>`).

###Head and Body
![] (http://i2.kym-cdn.com/photos/images/original/000/221/246/html_tattoo_9088.png)
HTML has  `<head>` and ` <body>` tags. The body contains the main contents of the HTML (every thing you can see) and the head contains the `<title>` tags (what you see on the browser tabs) and information for the page which your users dont see (link to style and Javascript files etc).
for example:
```
<head>
  <title> My First page </title>
</head>
```

### HTML Body
The content your users will see. In this session we will use:

1. Headings tags, ie `<h1>`H1 for your main heading,  `<h2>` `<h3>` `<h4>` `<h4>` `<h5>`(the smallest heading).
2. Paragraph tags `<p>` for text
3. List tags, these can be either ordered `<ol>` (with numbers), or unorder `<ul>`. Inside the opening list tags we add the list items `<li>`, these are nested like;
  
  ```
  <ul>
    <li> Item 1 </li>
    <li> Item 2 </li>
    <li> Item 3 </li>
  </ul>
  ```
  List tags are used to create many things that are not lists, including menu or navigation bars.
  
4. Div tags, `<div> </div>`  Div tags are not used for text, they are instead use to contain things, and are useful for styling.
5. `<a>` a Link tags, a tags provide links to different sites. The example below links to the W3 Schools site. 
  
  `<a href="http://www.w3schools.com">Visit W3Schools.com!</a>`
6. Images, add these with an `<img>` and a link. You can add images by uploading an image file and storing along with your webpage, or by linking to a url. The example below links a copy of the Founders & Coders Logo.
  
  `<img src="https://media.licdn.com/media/p/8/005/0a3/300/0f370ec.png" alt="Founders & Coders">`.

