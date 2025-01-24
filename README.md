# Yoga for All

Yoga for all is a website created for the studio 'Yoga for All' ´which is located in Nuremberg,Germany. It holds yoga classes for adults, children , prenatal yoga classes and yoga classes for new moms who want to start their fitness journey. It has both traditional yoga classes as well as fairly modern style of yoga as well like aerial yoga which makes exercise fun. Visit the live site [here](https://niraja85.github.io/Yoga-for-All/)

![Mockup](/docs/readme-images/mockup.png)

## Features

### Site wide
* Navigation menu
    * Contains links to website logo, home page, courses, gallery and calender pages which are responsive on all devices.
    * This will help users to easily navigate through the different pages without clicking the ‘back’ button.

    ![Navigation](/docs/readme-images/navigation.png)

* Navigation menu for mobile
    * The various page links are on the right side and visible on clicking the toggle. The logo remains on the left side.   

   ![Nav-mobile](/docs/readme-images/nav-mobile.png)

 * Footer
     * This will contain social media icons as links that  when clicked upon will open in new tabs. It is also accessible to visually impaired who maybe using a screen reader by the use of aria-labels. The second part of the footer on the left side contains the contact information with email id and phone number.  
     * These contact details will help people get in touch with me directly for any queries or any additional information user needs apart from that stated in the website.

     ![Footer](/docs/readme-images/footer.png)

* Favicon
    * A site wide favicon has been implemented with an image as an emblem on the tabs header.
    * This will help users identify the website in the tabs header if multiple tabs are opened.
    
    ![Favicon](/docs/readme-images/favicon.png)

* 404 Page
    * A 404 page has been implemented and it will be displayed if the user provides any broken link.
    * The 404 page will help the user to easily get back to the main page if they direct to a broken link 
      without the need of a back button.

![404 error page](/docs/readme-images/404error.png)

### Landing page

* Landing page image
    * It has an attractive and eye-catching image of a person doing yoga in the nature, directing the user to wards the calmness yoga practice brings.
    * This also has an overlay text which will directly guide the user about what the website is about.

    ![Landing page image](/docs/readme-images/landing.jpg)

* Website information about YOGA FOR ALL studio
    * The about me section focuses on the goal of the studio, yoga benefits, who can benefit from the classes, the working hours, and the cost.
    * It also has a clickable link 'calender' which can direct the user to the calender.html to view course schedule.
    * The information lets the user know about the website.

    ![About website](/docs/readme-images/about.png)

* Contact Form
    * A contact form has been added to enable users to contact 'YOGA FOR ALL' studio. It will consist of the following fields and attributes:
        * First Name (required, type=text)  
        * Last Name (required, type=text)
        * Email Address (required, type=email)
        * Message (required, type=textarea)
    * On submitting the form successfully, the user will be directed to thankyou.html indicating successful form submission.
    * This will help the users to contact the studio to join the different types of yoga classes, ask information about timings, cost or anything specific related to the courses.

    ![Contact Form](/docs/readme-images/form.png)

    ![Contact Form received](/docs/readme-images/form_received.png)

### Courses page
* Yoga Courses
    * Here a brief description about yoga and and its health benefits is given. Then descriptive explanation about different yoga styles has been explained with the guideline about who all can benefit from it. This will help the user streamline the kind of practice they wish to enroll for.
    * Images of the various yoga style has been added to give a visual overview of the different styles of yoga. 
    * It also has a clickable link 'here' that directs the user to the gallery.html page so that they can have a look of the photos of the yoga classes.

    ![Courses](/docs/readme-images/guide.png)

    ![Type1](/docs/readme-images/yogatype1.png)

    ![Type2](/docs/readme-images/yogatypes2.png)

    ![Type3](/docs/readme-images/yogatype3.png)

    ![Final](/docs/readme-images/yogatypes-final.png)

### Calender page
* Course Schedule
    * The schedule is displayed in tabular columns with days of the week as headings. This gives the user a clear idea about the different classes being held so they can plan accordingly.
    * The timings of the classes are displayed clearly and is made keeping in mind the work and school timings of the area, making it accessible to all age groups.
    * The table is responsive and the column display layout varies based on the device the user is using.

    ![Schedule](/docs/readme-images/class-schedule.png)

### Gallery page
* Gallery photos
    * The Gallery will provide user with variety of photos that are close examples of different types of Yoga classes done in the studio.
    * The gallery is responsive which will allow the user to view the photos on any device they are using.

    ![Gallery](/docs/readme-images/gallery.png)

### Existing Features
* Responsive design
* Interactive links on Home page and Courses page.
* Gallery is responsive
* Contact form and thank you page for successful form submission.
* Information on classes with modern and ancient yoga practice suitable for all.

### Features Left to Implement
* To add a collapsible toggle to close the toggle dropdown and better style it.
* To provide online yoga videos instead of only pictures.

## Design

### Framework
* General framework of the project was made in Word document, as the balsamiq access licence had expired.

![Design framework 1](/docs/readme-images/framework1.png)

![Design framework 2](/docs/readme-images/framework2.png)

![Design framework 3](/docs/readme-images/framework3.png)

## Technologies
* HTML
    * The structure of the website was developed using HTML as the main language.
*CSS
    *The website was styled using custom CSS in an external file.
* Cloud IDE
    * The website was developed using Cloud IDE.
*Github
    * Source code is hosted on Github and deployed using Git Pages.  
*Gitpod
    * It was used to commit and push the codes during development of the website.
*  Font Awesome
    * Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section. 
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce the size of the images used throughout the website
* Favicon.io
    * Favicon files were created at https://favicon.io/favicon-converter/  
* Microsoft Word 
    * Microsoft Word was used to write the general design and framework of the website.
* Pixabay
    * Pixabay was used to download the  free images from https://pixabay.com/
* Canva
    * Canva was used to design the logo of the website from https://www.canva.com/

## Testing

### Responsiveness    
* All pages were tested to ensure responsiveness on screen sizes from 320px and upwards.

* Steps to test:

1. Open browser and navigate to [Yoga for All](https://niraja85.github.io/Yoga-for-All/)
2. Open the developer tools (right click and inspect.)
3. Set to responsive and decrease width to 320px.
4. Click and drag the responsive window to maximum width.

Expected Results:
   * Website is responsive on all screen sizes and no image is stretched or pixalated.
   * No horizontal scroll present.
   * No elements overlap.

Actual Findings:

Website behaved as expected on all the browsers including Google Chrome, Mozilla Firefox, Safari and Microsoft edge.

Website was also opened on these devices and no responsive issues were seen:
    
1. Galaxy Z-Fold. 5
2. IPhone SE
3. Samsung Galaxy S20 Ultra
4. Google Pixel 7

### Accessibility

Manual Testing was performed to see if the website was accesible to all readers. Aria -labels were added and Alt text was used for all images to make the website accessible to people with visual impairent and can use screen-readers.

### Lighthouse Testing
![Lighthouse testing Home Page](/docs/readme-images/LH-home.png)

![Lighthouse testing Courses page](/docs/readme-images/LH-courses.png)

![Lighthouse testing Calender page](/docs/readme-images/LH-calender.png)

![Lighthouse testing gallery page](/docs/readme-images/LH-gallery.png)

### Functional Testing

* Navigation links

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page as shown below:

Home page - index.html
Courses page - courses.html
Calender page - calender.html
Gallery page - gallery.html

Links on all pages navigated to the correct pages as exptected.

* Contact Form testing

The contact form on the home page was tested to ensure it functioned as expected when correct data was entered and when incorrect data was entered. The following test scenarios were covered:

_Scenario One - Correct Inputs_

Steps to test:

1. Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

2. Scroll down to the contact form section and input the following data:

    - First name: Joe
    - Last name : Müller
    - Email Address : joe@gmail.com
    - Message: This is a test

3. Click 'Submit'

4. User should be directed to thankyou.html confirmation page.  

Expected:

Form submmission should be with no warnings or errors and user is redirected to thankyou.html confirmation page.

Actual:

Website behaved as expected with no errors or warnings and redirected to thankyou.html.

_Scenario Two - Missing Required Field First Name_

Steps to test:

1. Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

2. Scroll down to the contact form section and input the following data:

    - First name:
    - Last name : Müller
    - Email Address : joe@gmail.com
    - Message: This is a test

3. Click 'Submit'

Expected:

The form does not submit and an error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.


_Scenario three - Missing last name field_

Steps to test:

1. Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

2. Scroll down to the contact form section and input the following data:

    - First name: Joe
    - Last name: 
    - Email Address: Joe@gmail.com
    - Message: This is a test
3. Click 'Submit'

Expected:

The form does not submit and an error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.


_Scenario four- Missing Email address field_

Steps to test:

1. Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

2. Scroll down to the contact form section and input the following data:

    - First name: Joe
    - Last name: Müller
    - Email Address: 
    - Message: This is a test.

3. Click 'Submit'

Expected:

The form does not submit and an error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario five- Incorrect email format_

Steps to check:

1.  Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

2. Scroll down to the contact form section and input the following data:

    - First name: Joe
    - Last name: Müller 
    - Email Address: Joegmail
    - Message: This is a test

3. Click 'Submit'

Expected:

The form does not submit and an error is displayed to tell the user that the correct email address is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

* Footer social-media Icons / Links:

The Font-Awesome social media icons were tested to check if each of them opened in a new tab of their respective websites and when hovered upon turns orange for clicking.

Each item opened a new tab when clicked as expected and correct hover color was present.

* Footer contact information:

 Testing was performed by clicking on the telephone number provided in the 'contact us' section in footer to ensure behaviour was as expected.

 _Steps to test Telephone number_

 1. Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

 2. Click on the 'Phone' in the footer (01 234 567 789)

 Expected:

 A window opens asking to start a call.

 Actual:

 Behavior was as expected, and a window opened to ask to open facetime and when selected opened a window for call from my iPhone.

 _Steps to test the Email link_

 1. Navigate to [Yoga for All - Home page](https://niraja85.github.io/Yoga-for-All/index.html)

 2. Click on the email address in the footer (aiishniraja@gmail.com)

 Expected:

A windows popup is displayed from the default email application is asking to send an email.

Actual:

Behavior was as expected and my gmail account was opened ready to send an email to the target address.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)


  ![Home page validator results](/docs/readme-images/validator-home.png)

  ![Courses page validator results](/docs/readme-images/validator-courses.png)

  ![Calender page validator results](/docs/readme-images/validator-calender.png)

  ![Gallery page validator results](/docs/readme-images/validator-gallery.png)

- CSS
     - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

  ![CSS validator results](/docs/readme-images/validator-css.png)

### Unfixed bugs
Website was responsive on all devices but on landscape mode in mobile phones it behaved slightly differently with the variation seen in margin for header and main section. It could not be corrected even after putting various media queries.

## Deployment

### Gitpod

Gitpod was used to create the website and then pushed to github to the remote repository for 'Yoga-for-All'.

The following git commands were used to push code to the remote repo throughout the site development.

```git add .``` - This command was used to add the codes to the staging area before they are committed.

```git commit -m```- This command was used to commit changes to the local repository before they are pushed to github.

```git push```- This command was used to push all committed code to the remote repository on github.

### Deployment to github pages

* The site was deployed using Github pages. The steps taken to deploy the project are as follows:
    * In the GitHub repository, navigate to the Settings tab 
    * From the menu on left select 'Pages'
    * From the source section drop-down menu, select the 'branch': main, and the 'folder' to root.
    * Click 'Save'.
    * A live link will be displayed in green when published successfully.

The live link can be found here - https://niraja85.github.io/Yoga-for-All/

## Credits

* The information on different yoga styles were taken from [YogaMedicine](https://yogamedicine.com/guide-types-yoga-styles/) and added to the courses page.
* The design of the nav bar, toggle dropdown, the hero image and the gallery page was taken from [Love Running Project](https://niraja85.github.io/love-running/). I added the menu section on the right side using flex.
* The images on the gallery page were downloaded from [Pixabay](https://pixabay.com/) and optimised for webpages using [Web Optimiser](https://tinypng.com/)
* Valuable suggestions and ideas to align images were given by my mentor Gareth Mc.Girr.

### Future implementations

* Lighthouse testing's performance scores can be improved by optimising the images in a better way.
* Using Balsamiq to create wireframes can be added.

























    















    









    








       


 


        

    
         












        


[def]: /docs/readme-images/landing.png
[def2]: /docs/readme-images/form.png
[def3]: /docs/readme-images/yogatypes2.png
[def4]: /docs/readme-images/courses.png
[def5]: docs/readme-images/guide.png