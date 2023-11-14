# Horiseon Code Refactor

## Description

Within this task, I was given existing code from a marketing agency and was to refactor it to be as efficient as possible, add in aspects such as alt text for those who require the use of assistive technologies and leave the code clean, working and tidy. They wanted a codebase that followed accessibility standards and guidelines and code that was optimized for search engines. 

When first opening the code, I found a lot of div tags that needed replacing. This was the code when I first received it.
![Page of inital code I was given in VS code](<assets/images/MD Image 1.png>)


### I first went about assigning the correct semantic tags to each section accordingly. 

The Tags I used were: 

* Header - For the header of the website. 

* Nav - as this was a set of links to guide you to other areas of the website.

* Figure - This was self contained content. 

* Main - Where the main content of the website/page is. 

* Section - A specific part or section of the site/page. 

* Aside - This was the content on the side of the page not part of the main. 

* Article - This was content that was self contained within the Aside. 

* Footer - The footer of the website. 

I then moved into the CSS. Changing the previously assigned div tags accordingly. I then changed the classes in the 2nd section on the page to 'links' as within the css each had a seperate class tag but d all did the same thing. I tidied this up by changing all the applicable classes to 'links' I did the same thing with the 'benefits' section also.

I tided up areas of the code such as removing the 'class' from the aside as this is not needed because there is only 1 aside in the code. Another example was I removed the class from the footer for the same reason as above and changed from .footer to footer as there is only one footer the . was not needed. I have added comments with the css to show my working. Making the code easier to read and spot any other potential issues adds to the longevity of the code and website/page.

Next I reorginsed the order of the CSS to reflect the order of the HTML so it would be easier to follow and read.

Lastly, I added in alt text to all the images within the HTML. 

This is how my html looked at the end. 
![Edited and finished code from the project](<assets/images/MD Image 2.png>)


## Deployed Link
* [Click Here](https://atypicalbitter.github.io/horiseon-code-refactor/)

## Author
 * [Matt Dudman](https://github.com/atypicalbitter)