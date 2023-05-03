Download Link: https://assignmentchef.com/product/solved-cs224-homework-3-a-drawing-program
<br>
This assignment introduces SDL which is a C++ library for game development. We will use it later for our project. You will need to read the <a href="http://lazyfoo.net/tutorials/SDL/">SDL tutorials.</a> Lessons 1 and 6 contain instructions on setting up SDL and the extension library, SDL image, which are needed for this assignment.

A Drawing Program

In this assignment, you will be creating a drawing program. A basic version is provided in the accompanying folder Artistik. When run, it launches a white window in which you can draw a red rectangle by left clicking the mouse, dragging, then releasing.

Your will be extending this program as follows. Currently, every new shape overwrites the previous one. When you are done, the program will render each shape as either a line or a rectangle and all drawn shapes will be rendered. The user will be able to reset the window to clear all the drawn shapes and draw new ones. Each shape will be of a different color.

Your tasks are as follows.

<ul>

 <li>Read the SDL tutorials up to Lesson 10 in order to understand and run the given code.</li>

 <li>Declare a Shape class and inherit the classes Rect and Line from it. Line drawing is covered in the SDL tutorials above.</li>

 <li>Write a linked list in which each node stores a Shape*. Every added shape is stored in this list.</li>

 <li>Allow the user to switch between <em>line </em>and <em>rectangle </em> Line mode will be specified by pressing l or L and rectangle mode by pressing m or M.</li>

 <li>Assign a random color to each newly drawn shape. Use the Color object in Shape for the purpose.</li>

 <li>Allow the user to delete the most recently drawn shape by pressing d or D. Shapes can be deleted until no shapes are left, after which deleting has no effect.</li>

 <li>Allow the user to switch the rendering order of the shapes. By default, shapes are rendered in the order in which they are added. That is, the more recent shape is rendered later and ends up occluding the overlapping portions of any previous shapes. Pressing s or S switches the rendering order.</li>

 <li>Ensure that there are no memory leaks.</li>

</ul>