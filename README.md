# Udacity-IPN
<!DOCTYPE html>
<html lang="en">
<!-- This is an HTML Comment-->

  <head>
    <meta charset="UTF-8"> 
    <title> Introduction to Programming - Darrell's note</title>
    <!--title needs to be in the head, NOT inside the body-->
    <link rel="stylesheet" href="darrell-style.css">
  </head>

  <body>
    <div class="lesson">
    <div class="image"> <img src="images/oldmanatcomputer.jpg" alt="This is an image in the image file, it potrays an old man trying to learn how to use computer"> </div>
      <h1> Lesson 1: Basic of HTML.</h1>
    </div>
    <div class="lesson-description">
      <p>the web is a bunch of computers that communicate with each other.
        When a person type <em>something</em> in a broswer,
        that <em>something</em> is interpreted as <span class="italic"> HTTP Request</span> to the <em>server</em>.
        The server then finds the appropriate HTML document and send it back to the user, where
        a <em> web broswe</em> interprets the HTML document and displayes it on user's screen.
        <a href="https://www.udacity.com/course/viewer#!/c-nd000/l-3873828673/e-48329854/m-48480496">This video</a> does a good job of explaining interaction between user, browser, internet, and server.
      </p>
    </div>
    <div>
      <p>
        HTML stands for <em> Hypertext Markup Language</em> and it forms the marjority of the contents in the web. <br>
        <a href="https://www.udacity.com/course/viewer#!/c-nd000/l-3873828673/m-48724340">This video</a> explains what HTML is.
      </p>
      <p>
        HTML's code consists of a few <strong>elements</strong> with additional <strong>attributes</strong>.
        The following link explains what <a href="https://www.udacity.com/course/viewer#!/c-nd000/l-3873828673/m-48723444"><b>tags</b></a> are.<br>

        HTML elements are either <strong>inline</strong> or <strong>block</strong>. Block elements form an "invisible box" around the content inside of them.<br>

        Concept of <strong>span</strong> and <strong>div</strong> is also introduced. what is important is to remember that span is inline, "div" is block. Block elements form an "invisible block" around the contect inside of them
      </p>
    </div>
    <div class="lesson">
    	<h2> Lesson 2: Creating a structured document &#10647; HTML &#10648; </h2>
    </div>
    <div class="lesson-description">
    	<p>
    		<b>Developer tools</b> can be found in Google's setting and it helps to read how the codes of websites are being intepreted by the browser. It is very helpful to check how that HTML document is being structered
    	</p>
    	<p>
    		 The <b>"tree-like structure"</b> of HTML can have other elements inside of an element.
    		<br>In a broswer, the structure show us as a series of nested boxes.
    	</p>
    </div>
    <div class="lesson">
    	<h3> Lesson 3: Adding CSS (Cascading style sheet) to your HTML</h3>
    </div>
    <div class="lesson-description">
    	<p> 
    		Head tag in HTML is where you add your CSS link to your style file.
    	</p>
    	<p>	
    		CSS is code written to control the "style" of HTML Elements. For more useful information about selector, declaration, propety, value and also how to include CSS styling in web-page; refer to folllowing <a href= "https://classroom.udacity.com/nanodegrees/nd000/parts/0001345402/modules/383612889175460/lessons/4131369051/concepts/36111086980923">link </a> for more information.
        </p>

    	<p>
    		Search Engines use heading to index the structure and contents of the webpage.
    	</p>

    	<p>
    		<b> The box revisite</b>, the box model consists of 4 components, namely, margin, border, padding, and content.  https://youtu.be/jlp8uLzt16E. Because of many components in the boxes, it often be hard to get the size of a box just right. There are two techniques that can help to deal with these sizing issues.
    		<ol>
    			<li> Set Sizes in temrs of percentages rather than pixels.</li>
    			<li> Set the box-sizing attribute to border-box for every element.</li>
    		</ol>

    	<p>
    		<b>Positioning the box</b>, as Divs are <b>block</b> elements, so by default, they take up the entire width of a page. adding display:flex to an appropriate CSS is a powerful technique if you wants the parent container's sub-sections to be next to each other. https://youtu.be/sv2rVjnYfGQ
    	</p>

      </div>
    </body>
  </html>

<!--i can alwasy refer to Andy's example http://codepen.io/afumagalli/pen/dYgPRb -->
<!--Office Hour: p1. Make sure that your tags are nested-->
