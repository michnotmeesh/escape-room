# escape-room

You were at the zoo and accidentally let the animals loose! You're on the run and come across a brick wall with three suspicious doors! Which door will you choose? Where will it lead?!

![Final Product Example](https://github.com/junior-devleague/escape-room/blob/master/assets/example.png)

## Objective

Use **HTML Links, Images, Headers** and correctly specify the file paths to lead us to a new place at each door.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of CSS (Selectors, Basic Properties like Width and Height)

## Concepts

HTML | Description
-----|------------
HTML | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages.
element | An element is an individual part, or a building block, of a web page.
attribute | A modifier of an element.
div | A container element.
img | An image element.
a | A link element.
href | An attribute used to specify the link destination.
id | A unique attribute on an element used for targeting in CSS.
class | An attribute that can be applied to multiple elements used for targeting in CSS.

File Paths | Description
---------- | -----------
File Path | Describes the location of a file in a web site's folder structure.
Absolute File Path | Full URL to an Internet file. Ex. https://www.w3schools.com/images/picture.jpg
Relative File Path | Path to a file relative to the current page. Ex. assets/example.png

Relative File Paths | Description
------------------- | -----------
images/picture.jpg | Goes into the images folder, then points to the picture.jpg.
../images/picture.jpg | Goes outside of the current folder, then goes into the images folder, then points to the picture.jpg.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
* Folder called "rooms"  
3. Link all of your files correctly.

Make sure you have the assets from the repository as well.

### Part II HTML

To complete Part II, fulfill the following requirements:

1. Create a ```div``` with an ```id``` of "container".
  * **Inside** of this div, create the following:
    * A link element *Do you remember the tag name for a link element? Look at the table above!*. **Inside** of this link element, create an image element with ```id``` of "door1" and ```class``` of "door".
    *  A link element. **Inside** of this link element, create an image element with ```id``` of "door2" and ```class``` of "door".
    * A link element. **Inside** of this link element, create an image element with ```id``` of "door3" and ```class``` of "door".

    **Specify the right ```src``` for the image. Find the door image in the assets folder. Create the path to specify the door image and place that in the img src!**

2. Inside of the rooms folder, create 3 HTML files as follows:
* dungeon.html
* outer-space.html
* the-future.html

3. Now go back to the index.html file. When we click on one of the doors we want to be linked to another HTML file! How do we do that? We need to use a relative URL to specify the location of our HTML file! How do we go from where we currently are in the index.html to the dungeon, outer-space, and the-future HTML files?
  * In the ```href``` attribute of the 1st link element, specify the path to the dungeon.html file.
  * In the ```href``` attribute of the 2nd link element, specify the path to the outer-space.html file.
  * In the ```href``` attribute of the 3rd link element, specify the path to the the-future.html file.
