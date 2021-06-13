# Spin Expert

Spin Expert is a site for people interested in starting spin classes or beginner spin cyclists to find more information about the benefits of spinning, what to expect from a class, what equipment is needed, and where they can find a class locally. 

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

- __The benefits__

  - The benefits will give the user a brief summary of some of the health & wellbeing benefits of spin classes.
  - The user should feel equipped to make a decision about whether or not to take a spin class after reading this section.

- __First class checklist__

  - The checklist will list the various pieces of equipment a first-time rider should have, and also include some pre-class preparation tips.
  - The first class checklist will allow users to feel confident that they have what they need and know what to expect before their first spin class. 

- __Class picks__

  - This section will allow the user to identify the best type of class for them (e.g. Power Zone, Low Impact, etc.) and the time it's on this week. 
  - This section will be updated as new class types become popular or their details change.

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Spin Expert, helping users find other like-minded people.
  - Community is important to users as they will be able to ask questions, find other resources, and get feedback / encouragement.

### Features Left to Implement

- __Community forum & signup__

  - This section will allow users to talk to other site users to ask questions and provide support. Users should be able to sign up with their email address or a social media account via OAuth.

## Testing 

I have confirmed that each section of the site displays well across a variety of screensizes, using media queries to adjust certain elements for different screen sizes as needed.

I was keen to "bake in" responsiveness in some sections by using card design patterns with concepts such as flexbox, which I read about when studying the css fundamentals course. This allowed me to make both the first class checklist and class picks section to reconfigure the layout automatically, without media queries. I also used the techniques I learned in the Love Running project to create the benefits section in a way that required media queries; this seemed considerably more cumbersome than using small, fixed-size elements that can move from horizontal rows to stacked columns dynamically, though I recognise that both techniques have their pros and cons.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 
