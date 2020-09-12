
# **Ernest's Code Refractor Readme.**

![Stock Image](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/stock%20image.jpg)





This is a detailed description that will outline the first project of this BootCamp. The project is a code refractor operation, which a client wanted me to make his code more appropriate in regards to Semantic HTML. The timeline for this project is 1 week, and I will go in and make necessary changes to the client's code through my extensive experience from the UC Berkeley Extension Institution and along with my core analytical problem solving skills. In addition I will be referencing information from sources that illustrate the correct practices for refractoring HTML. 



If you have any questions feel free to contact me via Slack. 


## HTML/CSS Code REFRACTOR:

On Tues. Sept. 8th I recieved the HTML code from Client. The code was filled with "div" tags and wasn't organized in a way for non-technical professtionals to understand. I provide a snap shot below to illustrate the actual code that I recieved. 

Snap Shot of Original Code:  


HTML Code:


![Code Snapshot](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/html%20full%20snap.png)



CSS Code:


CSS Shot 1

![Code Snapshot](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/css%20code%201.png)


CSS Shot 2

![Code Snapshot](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/css%20code%202.png)






## Refractor Operation:

1. Filter out unecessary div tags for the core sections and replace them with more non-technical friendly tags for any reader to understand


    **Header Tags - Used the appropriate "Header" tag to illustrate the header area.** 



   ![Header Tag Image Example](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/header%20tag.png)



    **Main Tags - Used main tags to reveal the main content of the page.**


    
   ![Main Tag Image Example](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/main%20article%20tags.png)


    
    **Article Tags - Used these tags to identify the article or the space with important content**



    ![Article Tag Image Example](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/main%20article%20tags.png)



    **Aside Tags - I used these tags to associate key content on the side that supplemented the main content**



    ![Aside Tags Image Example](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/aside%20tag.png)



    **Added the image to the HTML and removed it from the CSS. Just for a cleaner look.**


    ![Added hero image to HTML](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/html%20hero%20img%20.png)

    

Illustration of these sections with descriptive tags in general is very helpful especially for developers so they know exactly where to go if they need to make changes. There are debug tools that are handy but there not always reliable. Strict project deadlines could result in not implementing descriptive tags, knowing the timeframe is important so the developer can create a plan to make all the necessary changes to meet the clients standards. 



2. Make changes to CSS the coressponds with the changes with the HTML above.



    **Made the header CSS class communicate with the HTML by removing the periods.** 

    Removed periods from the following header classes

    ![CSS Header class changes](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/header%20css.png)


    **Removed Background image link and added "object-fit: cover to maintain hero image from stretch**

    

    ![CSS changes to hero section](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/hero%20css.png)

    Changes Made

    ![After changes made to hero section](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/link%20and%20object%20fit%20cover.png)



     **Created 3 aside sections and slacked out the other sections to consoladated the code**


    
    Added "Aside" class for h3 section

   ![CSS Aside class "h3" dchanges](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/aside%20css%20h3%20tags.png)


    Added "Aside class for image (img) section

    ![CSS Aside class img section changes](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/aside%20css%20img%20tags.png)

    Added "Aside" class for this section

     ![CSS Adding Aside class for this section](https://raw.githubusercontent.com/HEEM86/Code-Refractor-EW/master/README%20images/aside%20css1.png)




    The goal is to consolidate the CSS as much as possible. There were sevaral areas of redudancy, where I created 1 class that reflected large sections of the HTML code. From an aesthetic perspecitive I think this is a good practice for being able to go back and quickly understand what parts of the HTML and CSS are communicating.  














