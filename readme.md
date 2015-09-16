##Geekwise Introduction to CSS
###Wednesday
###Date: 09-16-2015
###geekwise.kingsburg.sept15

##1: Overview

###Review important concepts from the prior day
* Reviewed the basic resume using `HTML` and `CSS`
* <http://geekwise.github.io/geekwise.kingsburg.sept15.resume.basic/>
* We had an overview of font size using `CSS`
	* pixels `font-size:16px`
	* em `font-size:1em`
	* percentage `font-size:100%`
	* relative keyword `font-size:medium` 

	> All the same size on the browser.
	> 16px,1em,100%,medium (these are the baselines for font sizes on the internet)

	### `CSS` Font Size Options:
	*  Length For Size: (32px,2em)
	*  Relative Size: (large)
	* Percentage: (200%)

### _A few reminders about nameing an `id` and `class`_


####Naming a `CSS` `ID` and `CLASS`:
* `ID` names **_only_** begin with a letter `[A-Za-z]` and may be followed by any number of letters, digits ([0-9]), hyphens `-`, underscores `_`, colons `:`, and periods `.`

####The difference between a `CSS` `ID` and `CLASS`:
* The difference between a `class` versus an `id` is that an `ID` `#id_name`selector is for something specific. A `CLASS` `.class_name` is reusable


##2:Share what you will learn today

###Review important concepts for the day.

* Introducing the `<link>` and `<meta>` tags for controlling the browser for basic `responsive` web design for mobile.

* <http://geekwise.github.io/geekwise.responsive.viewport/>

### 3: Practice exercise related to concept and objective
* Working and presenting as a team your one page team site
 
### 4: Closing session and circling back to objective of the day
* Combing tags
* Creating a full HTML one page site
* Answer questions about exercise
* Use <http://www.codepen.io> with new HTML tags we will be using tomorrow <button> and linking tags to new pages as well as different parts of a page. 

---
#1: Anatomy of an HTML Tag

### Each tag has a "start tag", "end tag", some content in between, and optional attributes.

```
<tagname attribute="value">
  content
</tagname>

<a href="http://www.google.com" >
  Google
</a>

<img src="https://avatars0.githubusercontent.com/u/1342004>
```

## What was taught the day prior?
* Combining Tags And Attributes To Build Links And Images That Are "Clickable"

Think of a `tags` as a `commands` to the `browser` and of the `attributes` as a way to `modify` that command.


## The html tag is always the first tag in the page.
```
<!DOCTYPE html>
<html>
</html>
```


## Head & Body

The head contains "meta" information about the page, information that the browser needs before rendering it.

The body contains the actual content of the page.

```
<!DOCTYPE html>
<html>   
 <head>
  <meta charset="utf-8">
  <title>Title of your website page</title>
 </head>
 <body>
		 	Our website!
  </body>
</html> 
```

## What goes in the body?

### Headlines

```
<h1>Header 1</h1>
<h2>Header 2</h2>
...
<h6>Header 6</h6>
```

### Paragraphs
```
<p>Paragraph 1</p>
<p>Paragraph 2</p>
<p>Paragraph 3</p>

Paragraph 1

Paragraph 2

Paragraph 3
```

### Line Breaks
```
<p>
This is a short <br>
Story about how <br>
Line Breaks <br>
Work in HTML <br>
</p>
```

### Lists
```
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  ...
</ul>

    Item 1
    Item 2
```

### Ordered Lists
```
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  ...
</ol>

    Item 1
    Item 2
    ... 
```

### Formatted Text
```
<em>Emphasized Info</em>

Emphasized Info

<strong>Important Info!</strong>

Important Info! 
```

### Images
```
<img src="http://www.google.com/images/srpr/logo1w.png" 
  alt="Google">
```

### Links
```
<a href="http://www.google.com">Google</a>
```

### Images with links
```
<a href="http://www.google.com">
<img src="http://www.google.com/images/srpr/logo1w.png" 
  alt="Google">
</a>
```

#Extra Reference
## A list of all the colors you can use in HTML
<http://geekwise.github.io/colors/>