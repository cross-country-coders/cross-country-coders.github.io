<h2> Cross Country Coders </h2>
<hr>
<h2> Table Of Contents </h2>
* [IMPORTANT LINKS](#important-links)
* [OVERVIEW](#overview)
* [PROJECT](#project)
* [USER GUIDE](#user-guide)
* [PEER REVIEW](#user-review)
* [DEVELOPER'S GUIDE](#develop's-guide)
* [TEAM MEMBERS](#team-members)

## Important Links
<ul>
<li>Link to the <a href ="https://github.com/cross-country-coders/algo-trix">GitHub Repository</a></li>
<li>Link to the <a href="https://github.com/cross-country-coders/algo-trix/releases/tag/0.2">Release Version</a></li>
<li>Link to the <a href ="https://github.com/cross-country-coders/algo-trix/wiki">Wiki</a></li>
<li>Link to the <a href ="https://github.com/cross-country-coders/algo-trix/blob/master/doc/ICS427A-5_%20CrossCountryCoders.pdf">Documentation</a></li>
</ul>

## OVERVIEW
The application Algo-Trix provides college or high school students with additional assistance to Algorithms outside of a textbook. It contains a list of different topics with mini explanation and study tips. It will also contain some sample problems and example problems.

* Landing Page
![](images/landing1.png)
<br/>
The landing page, is the first page that users will see when the visit the website. It will contain all of the topics covered in ICS 311.
* Log In Page
  ![](images/login1.png)
  If a user already has an account they can re-join using the log in page.
* Home Page
  ![](images/home2.png)
  <br/>
  This is the home page, it will display all the problems the user can do while logged in.
* Navbar
  ![](images/navbar2.png)
  <br/>
  This is our navbar to help users find the page they are looking for.
  ![](images/signout2.png)
  We also added a 2-step sign out popup.
* Sign Out Page
  ![](images/signoutPage1.png)
  This is our simple sign out page, more will be added in the future.
* Profile Page
  ![](images/profile1.png)
This is our profile page where users can see their progression as well as edit their profile and change their password.
* Register Page
![](images/register.png)
Otherwise if they do not have an account they can register by using the first name, last name, email, password and optionally an image.
* Problem and Explanation Page
![](images/problem.gif)
The application will contain a brief explanation and some rundown of sample problems for each topic covered in a typical Algorithms course. <br/>
On the bottom there will be a tabbed component with example problems that a modal page will pop up for solutions.
* Admin User List
![](images/userlist1.png) <br/>
If the specific user has a role of an admin, they can take a look at the user list that contains the first name, last name, and email but not the password for security purposes.

## Project
Here is a <a href ="https://github.com/cross-country-coders/algo-trix/projects/1">link</a> to the Project Board filled with different issues worked on. <br/>
<b>Accomplished Progress</b>
<ol>
 <li> <b>Week 1 (May 24)</b> </li>
 <ul>
  <li> Creating the GitHub organization repository and web page using GitHub pages. </li>
  <li> Mock Up Design: Creating the different mock up designs for each paage of the application. </li>
  <li> Using Intellij, started making the mockup designs into real Javascript code and creating the collection necessary for UserInfo login.</li>
  <li> Creating the different Navigation Bars one for the Landing Page (where the users are not logged in) and the Side Navigation Bar used once logged in. </li>
  <li> Created the Sign in and the Register Page. </li>
 </ul>
 <li> <b>Week 2 (May 31)</b> </li>
 <ul>
 <li> Created a User Profile Page.</li>
 <li> Created Admin Related pages, such as the User List where the Admin can see each user's first name, last name, email, and profile image. </li>
 <li> Making tune ups to the Side Nav Bar in terms of CSS. </li>
 <li> Created a list of fake but believable users. </li>
 <li> Created a collection that stores the different possible lessons. </li>
 </ul>
<li> <b> Week 3 (June 7)</b></li>
<ul>
<li> Created a Model for the Login/Register instead of it havin it as a whole individual page.</li>
<li> Create a Edit Profile Page </li>
<li> Created the Sorting Algorithm Pages and the Proof Pages.</li>
</ul>
<li><b>Week 4 (June 14)</b></li>
<ul>
<li>Created the MST Page</li>
<li>Created the Single Shortest Path Page</li>
<li>Created the Basic ADT Page</li>
<li>Created the Introduction to Graph Page</li>
<li>Created the Contact Page</li>
<li>Created the Growth Page</li>
</ul>
<li><b>Week 5 (June 20)</b></li>
<ul>
<li>Fixed the documentation of the application</li>
<li>Fixed the SideNavBar for the Admin User</li>
<li>Created the Red Black Tree and 2,3,4 Tree Page</li>
<li>Create a Binary Search Tree Page</li>
<li>Created the Logo for the Application</li>
</ul>
</ol>
<b>Future Updates</b>
<ul>
<li>Create a level system based on the lesson accomplishment</li>
<li>Create a book marking system where users can book mark their progress or lessons to look back again</li>
<li>Create video lessons unique to the application.</li>
</ul>

## Developer's Guide
<p> Here is a brief step to step on how to run the application.</p>
<ol>
<li>To download the source code please head over to the <a href="https://github.com/cross-country-coders/algo-trix">repository page</a> and download the master branch.</li>
<li>Then, install meteor in the app folder using this following command: <code>meteor npm install</code>
<img src="images/install.png"> <br/></li>
<li>Then type in <code>meteor npm run start</code> then go to the following link <code> http://localhost:3000</code> to see the application running locally in your computer. </li>
<img src="images/run.png"> <br/>
</ol>

## Team Members 
Here it lists all the team members of the Cross Country Coders and the contributions that they have made for this project. 

* [Jerome Gallego](https://alohajerome.github.io/)
  * Contact: gallego6@hawaii.edu
  * Interests: Software Engineering
  * New Completion (June 19)  
    * Created the Profile Page
    * Fixed erros with Profile Page
    * Created the Mock Up designs for the Contact Page
    * Fixed most of errors on the mock-up version of the Contact Page
    * Normal clean up on javasript code
  * Current (June 27)
    * Adding the drop down for why you should contact the admin
  * Next (June 27)
    * Continue to clean up javascript code on files that are not being used
    
* [Christian Jensen](https://christianjensenv.github.io/)
  * Contact: cjensen6@hawaii.edu
  * Interests: Software Engineering, Video Game Development
  * New Completion (June 27):
    * Created the SideNav Bar Component for the Application
    * Add 2 step sign out
    * Created the CSS Designs that applies for most of the pages
    * Finding practice problems.
    * Create and add logo to website tab
    * Creating a simple level up system
    * Add prereq dropdown for sidebar
  * Current (June 27)
    * Connecting level up to user
    * Looking for any needed visual improvments
  * Next (June 27)
     * Looking for sample problems for the website
    
* [Jun Miao](https://junm1ao.github.io/)
   * Contact: junmiao@hawaii.edu
   * Interests: Software Engineering, Database Management, Mobile App Development
   * New Completion (June 27):
     * Created a stronger faker user generator system.
     * Created the Login/Register Modal.   
     * Fixed the User List Page for Admin to display the user count on the page itself and the side nav bar
     * Fixed the Edit Profile Page into Modal.
     * Fixed the file and improved up on ESLint errors.
     * Created the Runtime Pre-req lesson page.
     * Created the Github Wiki Page
     * Merge some components into the landing page
  * Current (June 27)
    * Creating Lesson Pages.
  * Next (June 27) 
    * Finding good sample problems to place on the lesson page.
* [Shinya Saito](https://saitoshi.github.io/)
  * Contact: saitoshi@hawaii.edu
  * Interests: Software Engineering, Mathematical Teaching, Japanese and English Translations, Design
  * New Completion (June 27)
    * Created the UserInfo Collection 
    * Create the Basic User Fake Generator 
    * Created the Landing Page 
    * Created the Sorting Algorithm Lesson Page 
    * Created the Proof Writing Lesson Page 
    * Created the Rough Contact Page
    * Created the Home Page when users login
    * Creating the PreReq Material Lesson Pages for Algorithms  
    * Creating the Single Short Path Page
    * Creating the Basic ADT Page
    * Creating the Introduction to Graph Page
    * Creating the MST Page 
    * Creating the Binary Tree Page
    * Create 2-3-4 and Red Black Tree  
  * Current (June 27)
    * Create a Stronger Sets of Problems
  * Next (June 20)
    * Creating the Pages for other algorithms related to Graphs.
    
<h3>Closing Thoughts</h3>
<b>Difficulty</b>
<ul>
<li>The assignment was difficult because all the team members were in different locations with some having a different time zone compared to Hawaii.</li>
<li>Creating different problems and set of notes were challenging.</li>
</ul>
<b>Take Back</b>
<ul>
<li>Since the application was Algorithm lesson based, it gave the creators a good review on topics learned in algorithm such as Red Black Tree, Sorting Algorithms, etc.</li>
<li>Probably should have created a stronger schedule as the schedule that was followed may have been too weak.</li>
</ul>
