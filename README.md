# portals

Are you ready to teleport?

## Objective

Use **HTML Links** to create page jumps and links to other websites.

## Prerequisites

To complete this project, students should have the following:  
* Basic understanding of HTML structures and attributes.
* Basic understanding of Flexbox.

## Concepts

HTML | Description
-----|------------
HTML | **H** yper **T** ext **M** arkup **L** anguage used to create the structure of web pages.
element | An element is an individual part, or a building block, of a web page.
attribute | A modifier of an element.
nav | A navigation element*.
ul | An ```unordered list``` element.
li | A ```list item``` element.
a | A ```link``` element.
href | An attribute used to specify the link destination.

CSS | Description
----|------------
CSS | **C** ascading **S** tyle **S** heets that describes how HTML elements are displayed.
flexbox | A layout mode to improve how items are aligned or ordered on a page even within items of unknown size.
margin |  The outer space of an **element**.
padding | The inner space of an **element**.

Note: Flexbox comes in very handy! It is helpful to remember the following common CSS Flexbox properties.
* ```display: flex;``` Use this to activate Flexbox! If you do not have this property, other flexbox properties will not work.
* ```justify-content: center | space-around | space-between;``` Control horizontal spacing.
* ```align-items: center | space-around | space-between;``` Control vertical spacing.
* ```flex-direction: column | row;``` Control the direction of items.

## Your Challenge

### Part 1

To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML file
* CSS file
3. Link all of your files correctly.

### Part II HTML

To complete Part II, fulfill the following requirements:

1. Create a ```div``` with a ```class``` of "container".
* **Inside** of this div, create the following:
  1. Create a ```nav``` with an ```id``` of "nav-bar".
      * **Inside** of this nav, create a ```ul``` element.
         * **Inside** of this ul, create **3 li** elements.
            * Each ```li``` will contain an ```a``` element as follows. The ```href``` attribute will contain a page link that will take us to the section with that id on the page.

            ```
            <ul>
              <li><a href="#green-portal">Green!</a></li>
            </ul>
            ```

            * For the first ```li``` element, set the ```href``` attribute to "#green-portal". In the text portion of the element, set it to "Green!".

            * For the second ```li``` element, set the ```href``` attribute to "#yellow-portal". In the text portion of the element, set it to "Yellow!".

            * For the third ```li``` element, set the ```href``` attribute to "#red-portal". In the text portion of the element, set it to "Red!".

  2. Create a ```div``` with a ```class``` of "section" and ```id``` of "welcome".
      * **Inside** of this div, create an ```h1``` element. In the text portion of this element, type out a greeting to the person that's on your page!

      ```
      <div class="section" id="welcome">
        <h1>Welcome wanderer, which portal will you choose?</h1>
      </div>
      ```
  3. Create a ```div``` with a ```class``` of "section" and ```id``` of "green-portal".
      * **Inside** of this div, create the following:
          * Create an ```h1``` element with some text to greet the person that arrived at this part of your page.
          * Create an ```a``` element. In the text portion type out "Somewhere Green!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere green.
          * Create an ```a``` element. In the text portion type out "Somewhere Peaceful!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere peaceful.
          * Create an ```a``` element. In the text portion type out "Somewhere Grassy!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere grassy.

  4. Create a ```div``` with a ```class``` of "section" and ```id``` of "yellow-portal".
      * **Inside** of this div, create the following:
          * Create an ```h1``` element with some text to greet the person that arrived at this part of your page.
          * Create an ```a``` element. In the text portion type out "Somewhere Yellow!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere yellow.
          * Create an ```a``` element. In the text portion type out "Somewhere with Sunshine!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere with sunshine.
          * Create an ```a``` element. In the text portion type out "Somewhere Smiley!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere smiley.

  5. Create a ```div``` with a ```class``` of "section" and ```id``` of "red-portal".
      * **Inside** of this div, create the following:
          * Create an ```h1``` element with some text to greet the person that arrived at this part of your page.
          * Create an ```a``` element. In the text portion type out "Somewhere Red!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere red.
          * Create an ```a``` element. In the text portion type out "Somewhere Warm!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere warm.
          * Create an ```a``` element. In the text portion type out "Somewhere Happy!". In the ```href``` attribute, copy and paste the URL of a website that depicts somewhere happy.

### Part III CSS

To complete Part III, fulfill the following requirements:

1. Target the ```class``` of "container".
* Set the ```height``` to ```calc(100vh)```. This value will calculate the full view height (vh).
* Set the ```width``` to ```calc(100vw)```. This value will calculate the full view width (vw).
2. Target the ```id``` of "nav-bar".
* Set the ```width``` to 100%.
* Set the ```height``` to 10%. This means that your navigation bar will be 10% of its parent's height. In this case, the parent element is the container because nav element is within the container.
* Activate Flexbox!
* Center the items horizontally and vertically using Flexbox.
* Set the ```font-size``` to 50px.
3. Target the ```ul``` element. *Hint: How do we target elements by themselves, without classes or ids?*
* Set the ```width``` to 50%.
* Set the ```height``` to auto. Auto will automatically set the height of the ```ul``` element to be whatever the height of the inner items are.
4. Target the ```class``` of "section".
* Set the ```width``` to 100%.
* Set the ```height``` to 400px.
* Set the ```margin-top``` to 2000px. This makes the items very far apart from each other.
5. Target the ```id``` of "welcome".
* Set the ```margin-top``` to 0px. This overrides the ```margin-top: 2000px``` that we set on its class because we are targeting this item more specifically (id is more specific than class).
6. Target the ```id``` of "green-portal".
* Set the ```background-color``` to green.
7. Target the ```id``` of "yellow-portal".
* Set the ```background-color``` to yellow.
8. Target the ```id``` of "red-portal".
* Set the ```background-color``` to red.

Now, check your items in the browser and try clicking on the links! Are they taking you to the right places?

### Stretch Goals
1. In each colored section, create a link that will take the users back to the top of the page!
2. Add an image to each section!
