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
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fharryowens.github.io%2FSpin-expert%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fharryowens.github.io%2FSpin-expert%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

None observed.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://harryowens.github.io/Spin-expert/


## Credits 

### Content 

- The text for each section is original and written by me
- The header and benefits section was heavily influenced by the Love Running project from Code Institute
- The cards for the checklist were derived form an example on [W3Schools] (https://www.w3schools.com/howto/howto_css_cards.asp)

### Media

- The photos used for the hero image, benefits section and checklist are from Unsplash
- The images used for the spin class instructors are from their profiles on onepeloton.com
