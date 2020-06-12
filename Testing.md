### Testing:
   ------------
   - **HTML:** The HTML Validator https://validator.w3.org/ was used to validate the HTML code.
   - **CSS:** The CSS Validator https://jigsaw.w3.org/css-validator/#validate_by_input was used to validate the css code.
   
   When running both of these validators in the beginning i found a few errors mainly typos and trailing div's. There were also some warnings for code that was correct and could be ignored. On correcting what needed to be corrected,  the code works well.
   <img width="250" height="300" src="readme-images/ss-index01.jpg">
### Testing with user stories:

* As a parent , I want to find a place where my child can learn about horses and how to ride.
    - Open the Ruby's Riding Center Website.
    - Scroll down on the page to the middle and read what the children are encouraged to do.
    - Go to the navigation bar at the top right of the page
    - Click on the Lessons page
    - Scroll down to the middle of the page
    - Read about what the children are taught in a lesson
    - Scroll down to the bottom of the Lessons page to the Riding Video
    - This gives a short view of what a proper lesson entails.

* As a parent, I want to build my childs confidence.
* As a parent, I want my child to have fun while being safe.
    - Open the Ruby's Riding Center Website.
    - Scroll down on the page to the middle and read what the children are     encouraged to do.
    
* As a parent, I want to hear what others have to say about the place.
    - Open the Ruby's Riding Center Website
    - Scroll down to the bottom of the page
    - Read what other parents have to say
    - Go to the navigation bar in the top right of the page
    - Click on the Contact page
    - On the page you will see map with all the contact details below
    - Contact the Riding Center for further information
    - You can also fill in the message form
    - Fill in the "Full Name" field, "Email" field and the "Message field", if the form is filled in correctly, click on the submit button, it then goes to the top of the page and the form clears.
    - BUG: The "Full Name" fiel accepted all characters and numbers. Needed to validate it so it only accepted letters.
    - If the "Email Adress" field is not correctly filled in, and error appears, please include "@" in the email address.

* As a parent, I want my child to feel normal.
    - - Open the Ruby's Riding Center Website
     - Read through the home page and the lessons page to get a feel of the Riding Center.
    - Go to the navigation bar in the top right of the page
    - Click on the Accessories page.
    - Enjoy looking at all the childrens riding gear for sale.
    - Scroll to the bottom of the page, you will find a bi-weeekly newsletter sign up.
    - Fill in your email correctly.
    - Click sumbit
    - The Bi-weekly newspaper lets you feel like one of the family, gives you details on events and what is happening at the center.
    - If email is correctly filled in and submit button clicked it goes to the top of the page and the form clears.
    -If not correctly completed the error message says " please include "@".
    If this is included, eg 123@ the error message states "please enter part following "@", 123@ is incomplete.

### Features and responsive testing:

Chrome Dev tools was used alongside all my written code to make sure i was getting the responsiveness and size correct for the different pages.

- **Responsiveness per page**

- **Home Page:** 
    - On mobile the navigation bar is collapsed to a hamberger menu (three lines).
    - The "What We Encourage" section has the photos and descriptions aligned one under each other.
    - The "What Our Parents Say" section is also aligned one ontop of the other and looks neat.

    - On IPAD-PRO the navigation bar is expanded and you can now see the different page names.
    - The "What We Encourage" section now has 2 rows with 3 photos next to each other in each row.
    - The "What Our Parents Say" section is now in one row and the 3 stories are next to each other.

    - On Full screen the navigation bar is expanded and you can now see the different page names.
    - The "What We Encourage" section now has 2 rows with 3 photos next to each other in each row.
    - The "What Our Parents Say" section is now in one row and the 3 stories are next to each other.
  
- **Lessons Page:** 
    - On mobile the navigation bar is collapsed to a hamberger menu (three lines). On clicking it the navigation bar appears with all pages listed, so it is easy to move between the pages.
    - The "What We Teach" section has the photos and descriptions of the photos aligned one under each other.
    - At the bottom of the page is a description and insight into an actual riding lesson in the form of a short video.

    - On IPAD-PRO the navigation bar is expanded and you can now see the different page names.
    - The "What We Teach" section has now expanded into 3 pictures accross the page with the 4th below in a second row.
    ( I originally had the photos one below the other with the writing to the right of it but could not get the alignment correct. This way the alignment works.)
    - The video is responsive accross all page sizes.

    -On full screen the page looks the same as on the ipad-pro just a little larger.

- **Accessories Page:** 
     - On mobile the navigation bar is collapsed to a hamberger menu (three lines). On clicking it the navigation bar appears with all pages listed.
     - In the middle of the page is "Our Shop". The items and their descriptions are shown one below the next.
     - Each item has a "Buy Now" button which will in future link to a shopping cart.
     - At the bottom of the page is a sign up form for a bi-weekly newsletter, to people informed of events and upcoming compertitions and get togethers.

     -  On IPAD-PRO the navigation bar is expanded and you can now see the different page names.
     - The middle of the page now has the images 3 next to each other and then 3 rows down. There is space to add aditionoal items.
     - At the bottom of the page the sign up newsletter section is now expanded to cover the size of the lower page

     -On full screen the page looks the same as on the ipad-pro just a little larger.

- **Contact Page:** 
    - On mobile the navigation bar is collapsed to a hamberger menu (three lines). On clicking it the navigation bar appears with all pages listed.
    - In the middle of the page is an interactive map with the riding Centers contact address, email and contact number.
    - Below the map is the "Message us" form. A contact form for the parents to get hold of the riding center.
    - Below is a Beautiful photo of horses stating "We Look Forward To Seeing You" which leaves the client with a happy feeling.

    - On IPAD-PRO the navigation bar is now expanded and the page links can be seen.
    - In the middle of the page the map and the message form are now next together. ( i had a problem with them throwing the alignment out on the page, this is why they are so close together.)

    -On full screen the page looks the same as on the ipad-pro just a little larger.

   - **Web-dev:** Web-dev measures your site to see how well it supporst your users and what you can do to increase your rate of support. Handy little tool. 
    - **[My Report](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Flee-annc.github.io%2FRubys-Riding-Center)**

### Problems and bugs
- **Bootstrap and alignment:** The issue of allignment took me a very long time to sort out. With the help from the folks on slack and my mentor i found that my order for bootstrap was incorrect. I was directed to watch a video which Anna (one of the tutors) made just on bootstrap.
On correcting the order, things seemed to work better.
I still have a problem with overflow in the navigation top blue bar which i have been unable to correct.

* Contact form works as it should.
    * Go to the Our Newsletter Sign up
    * if the user does not enter an email the user will get the error - "Please include and @ in the email address".
    * If the user doesn not enter the email correctly and only
    enters abc@ the error message will say " Please enter the part following the @. This is incomplete.
* This works the same for the "Message Us form".
* this website is responsive from mobile up to large screen resolutions.

### Testing on Web Browsers:

The web browsers that i tested my site on were:
- **[Firefox](https://en.wikipedia.org/wiki/Firefox)** My site opened perfectly, and was fully responsive with no issues arising.
- **[Opera](https://https://en.wikipedia.org/wiki/Opera)** My site opened perfectly, and was fully responsive with no issues arising.
- **[Chrome](https://en.wikipedia.org/wiki/Google_Chrome)** My site opened perfectly, and was fully responsive with no issues arising.
- **[Safari](https://en.wikipedia.org/wiki/Safair)** On uploading my site to safari i noticed that the main image was too large, everything else on the site worked perfectly.