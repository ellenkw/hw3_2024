# Assignment Name: CSS Grid 

## Due Date: See Canvas

## Goals: 

You have been given image files, a starter CSS file, and an HTML file which has all of the required content to recreate the provided screenshot. Use only CSS to achieve the changes \- do not change the html file for styling (to add classes).

## Objectives: 

1. Demonstrate ability to use CSS Grid for layout of page content

2. Demonstrate ability to code a working “Skip to Content” link that is not displayed on the screen until it is in focus.

3. Demonstrate ability to add and style focus states.

4. Demonstrate ability to use media queries to adjust how page content displayed on different devices.

5. **Note: Do not use Flex for HW\#3**

## Resources:

[https://github.com/UMSIComplexWebDesign/HW3\_CSS\_Grid](https://github.com/UMSIComplexWebDesign/HW3_CSS_Grid)

You are provided with a repo that contains the necessary html file, a starter css file,  and a screenshot of the final results.  **You will need to edit the existing html AND css file** to transform the original page to one that resembles our example using the outlined CSS styles below.  ***Remember, resource files often have a few bugs in them to provide an opportunity to debug and problem-solve***.  The changes will be small.

**Images of the finished product are included in the file you downloaded from Github.**

### Hints for fixing index.html

1. Check the \<head\> element to ensure all of the needed metadata is present \-  including linking to the stylesheets properly. 

2. Fix the \<body\> element to make sure that all links in the page work correctly.  You may ***NOT*** add any new classes or ids to any of the tags but other attributes to fix validation errors (particularly focus) are allowed.							

## Requirements:

***Note, the css code has comments to guide you through these requirements.*** **Please don’t remove the comments.**

* All files and folders present, HTML file and CSS stylesheet in proper format, no styles in HTML. You will need to modify the HTML but  **do not add any classes or ids**.  You must use the classes and ids that we already provided.

1. Add an underline under any link in the nav that is in the **hover** or **focus state**.

2. The “Skip to content link” (the link within the skip class) should have the following styles on all screen sizes

   1. The link is positioned 40px above the top of its parent element (it is **hidden by default)**.

   2. When the link is in **focus** it is positioned 20px below the top of its parent (so it is visible only when in focus.)

3. Any element in focus should have a 2px solid border on all sides.

### **The following specifications are for the default/mobile view:**

4. .container class uses grid:  
   1. Three columns: 1fr 5fr 1fr  
   2. Gap of 15px between rows;  
      1. *Hint: review the Inspect Element images for this one*

      

5. The first child of the container should  
   1. Take up  all of the columns  
   2. Use the header.jpg file as a non-repeating background image with parallax effect  
   3. You can **NOT** assume that the .overview class will always be the first child.


6. The classes .about, .method, .clients, and .contact:  
   1. Begin in 2nd column and span one column  
   2. Begin on the 2nd, 3rd, 4th and 5th rows respectively.

7. The .about-image, .method-image, .clients-image,   and .contact-image elements:  
   1. Cover all of the columns.  
   2. Have a **maximum height** of 600px  
   3. Hide any content that goes outside their grid cell.   
   4. Begin on the 2nd, 3rd, 4th and 5th row respectively.

8. The .text-block class:  
   1. Is centered horizontally and vertically with centered text.  
9. Check your output against the screenshots provided 

### **The following specifications are for the desktop view (windows of 800px or greater)**

10. Move the navigation so that the nav is aligned to the other side of the window and has a padding of 30px on the top and bottom and 0 on the left and right.

11. The .container class uses grid with  
    1. Five columns: 50px, auto, 500px, auto, and  50px

12. The .about, .clients, .method-image, .contact-image:  
    1. Begin in the third column and span two columns

13. The .method, .contact, .about-image, and .clients-image:  
    1. Begin in the second column and span two columns.

14. The .text-block class:  
    1. Has  **maximum height** of  250px  
    2. Ensures that  any content that goes outside their grid cell is still reachable. 

15. Validate your code in all views and fix errors.

## Tips\!

1. Start with the css file and look for the places you should.  
2. ***Get the default (mobile view) complete before you start the desktop view.***  
3. If your rules cascade correctly, you should have fewer selectors in the desktop view

## Submission Requirements:

1. Upload your code to Github in a repo called **hw3\_2024**.  Make sure to link it to Github Pages so we can see your deployed code.  
2. Submit link in Canvas.  We want to see the **deployed page,** not the code so the URL should be http://\<your-user-name\>.github.io/hw3\_2024  
3. There is no autograder, but there is a rubric for you to follow.

***Reminder: Any changes to code after the due date can result in a late penalty at any time during the semester.  If you want to modify your code for personal use \- make a new copy.***

### **Grading Rubric \- copied over from Canvas\***

\* we will be giving partial credit where some things are done successfully. 

| Criteria | Ratings | Total Points |
| :---- | :---- | :---- |
| Add an underline | 2 pts Full Marks 0 pts  | 2pts |
| Style "The “Skip to content link” | 4 pts Full Marks 2 pts One of the appearances did not match example 0pts | 4pts |
| Any element in focus should have a 2px solid border | 4pts Full Marks 0pts | 4pts |
| Mobile view .container styling | 10pts full marks 0pts | 10pts |
| Mobile view \- Style the first child of the container | 10pts full marks 0pts | 10pts |
| Mobile View \- Steps 6 & 7: Style the other children of container | 10pts full marks 0pts | 10pts |
| Style .text-block class | 5pts Full Marks 0pts | 5pts |
| Large view nav | 5pts Full Marks | 5 |
| Large view grid | 15pts Full Marks 9pts for partially successful grid | 15 |
| Large view text class | 10pts Full Marks | 10 |
| **Validator error deductions** Any validator errors (wave, axe, w3 html, w3 css, etc) are an automatic 10 point deduction.  | 0pts There will be automatic deductions of 10 points for any validator errors | 0 |
|  |  | **Total: 75pts** |

