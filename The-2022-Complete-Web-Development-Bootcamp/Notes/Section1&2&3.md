# Some basic concepts/kits for starting the course
## Concepts
- Server: giant lib apply files and services 24/7
- a Tech news website - www.techcrunch.com
## Tools and Resources
- Chrome
- [Atom plugins](https://docs.google.com/document/d/e/2PACX-1vQNuhDC5pFXEVVNGasvddKuDHEXnqR033lsSD5tLA9NiEdHrsYM4MXVEXja2RnBgsCxK6XEo6YkMOFI/pub)
- [All the resources list for this course](https://www.appbrewery.co/p/web-development-course-resources/)
- Search all the useful doc principles here - [devdocs](devdocs.io)
- Read all  the shortcuts here : [doc of emmet](docs.emmet.io/cheat-sheet/)
- [MDN web docs](developer.mozilla.org/en-US/)

## Expanded Reading 
- [The absolute minimum every software developer absolutely, positively must know about unicode and character sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)


# Introduction to HTML
- HTML = HyperText **Markup** Language
- XML, GML, HTML.. they are all markup languages.

## The anatomy of a HTML tag
- closing tags or self-closing tags
	- Find the answers at tag omissions in [Devdocs](devdocs.io)

- HTML attribute and element
```HTML
<hr size = "3" noshade>
<!--Comment: create a horizontal line at size of 3 -->
```

- Now we are using HTML5 document.
```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <!-- Meta charset defines the characters we use in this file-->
    <!-- For utf-8, it includes all the international characters and even emojis -->
    <title>Feiyang(Sophia)'s Portfolio</title>
  </head>
  <body>

  </body>
</html>
```

## about `<meta attributes> 
- `<meta description = ''>`: let the browser know what's your page is about and how to display it on searching engine.

## about images in HTML
- `<img src="" alt="">` : img elements including attributes about the image's source and description


# Section 3 Intermediate HTML

## To Create a Table in the HTML
- table cells  `<td></td>` are horizontally placed.
- and table rows `<tr></tr>` are vertically placed.

# Examples
- [An great interactive resume](http://www.pascalvangemert.nl/#/profile)

## Forms 
- To create forms and labels, try different types of input.
-  in `form` attributes, we can change the `action` to change the website.
	- `action="mailto:info@helloworld@gmail.com"` use this could be use to guide to directly email to someone you put in the action.



