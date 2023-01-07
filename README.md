# Reimagine classical 

[Reimagine classical](https://aliceohio.github.io/reimagine.classical/) is a site for people who are interested in classical music but who may have never found the right music to fit their personal musical taste. 

Remembering the days of music recordings being available on vinyl, then the transition to tape cassettes, then on to cds and now to the multiple music apps where one can listen to everything, sometimes the choices are overwhelming.

As a classical music lover and musician I get frustrated by poor performances and I've yet to find an online music app that offers consistent good recordings from top-notch musicians. 

When you think of Debussy or Mozart you don't want to hear just anyone perform. What is it that makes a recording great as compared to just okay? It's about the performer's intimate knowledge of the piece they are performing, the hours of practice, the life experiences conveyed through the music. Music is not just about listening but about feeling. You should be able to feel the emotion of the musician coming through when you are listening (think of a live concert by your favorite artist vs an instrumental version you might hear in the elevator - one will definitely put you to sleep!)

My goal through this website is to create a service in which I help you to experience the same passion I have for classical music by creating a specific collection of classical pieces based on your current listening preferences. By asking a few questions initially, and through our contact after you fill out the "let's talk" form, I will take time to curate your individualized playlist.

## FEATURES

### Existing features:

- The Navigation Bar

    - The fully responsive navigation bar includes links to the home page, facts about classical music, about me and a let's talk section and is consistent throughout the website for easy navigation.

    - The navigation bar allows the user to move easily from one page to another, across all devices and layouts (portrait or landscape) without having to us the 'back' button.

    ![NavigationBar](/assets/images/Screenshot%20NavBar)
    
- The Landing Page

    - The landing page image is a pair of over-the-ear headphones with the logo of reimagine classical over the image.
    - There is a brief tag directly under clarifying the branding information.

    ![LandingPage](/assets/images/Screenshot%20LandingPage)

- The Footer

    - The footer section allows the user to visit my personal page on relevant social media sites, including my CV on linkedin. The links open in a new tab to allow for simplified user navigation.

    ![Footer](/assets/images/Screenshot%20Footer)

- The Classical Facts Page

    - The classical facts page shows six various images of musical instruments, musical devices (a metronome) and written music itself. 
        - On large screens, the images are clear and bright with no filter used.
        - On smaller screens, the images are blurred and have an overlay so the classical facts can be easily read.

    - The classical facts includes various facts about the advantages to listening to classical music, including its effects on heart health, psychological health, breathing rates, neurological advantages as well as its use in the treatment of pain.

        - On large screens, the facts present themself only with the use of a hover effect.
        - On smaller screens, the facts present themselfs without use of hover.

    ![ClassicalFactsClear](/assets/images/Screenshot-CFclear)

    ![ClassicalFactsBlur](/assets/images/Screenshot-CFblur)

- The About Me Page

    - The about me page is a brief overview of who I am, including my musical background as well as why I believe listening to classical music is beneficial to everyone.
    
    - This page includes two working hyperlinks, both of which open in new windows, for user ease.
        - The first link is an external link to a biography of a music teacher.
        - The second link in an internal link to the "let's talk" page to encourage interaction with the user.

    ![AboutMe](/assets/images/Screenshot-AM)

- The Let's Talk Page

    - The let's talk page allows the user to share with me a bit more about their current music preferences to provide a base for the initial contact.

    - The let's talk page uses an image of a vinyl record in the background with a transparent overlay so the text can be easily read.

    - The let's talk page includes:
        - a datalist dropdown menu for pronoun usage,
        - a text input for name,
        - a required email input,
        - a checkbox with four options for musical style preferences,
        - a textarea input for any additional information the user would like to share, and
        - a submit button.

    ![LetsTalk](/assets/images/Screenshot-LT)


## Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing
- HTML
    - No errors were returned when passing through the official W3C validator
    IMAGE
- CSS
    - No errors were found when passing through the official (Jigsaw) validator
    IMAGE

### WAVE Testing
- home page
    - No errors or alers were returned when passing through the offical web accessibility evaluation tool.
    IMAGE
- classical facts
    - No errors or alers were returned when passing through the offical web accessibility evaluation tool.
    IMAGE
- about me 
    - No errors or alers were returned when passing through the offical web accessibility evaluation tool.
    IMAGE
- let's talk
    - No errors or alers were returned when passing through the offical web accessibility evaluation tool.
    IMAGE

### Lighthouse Testing
- The entire website scored very well throughout, with accessibility consistently at 100%.

- home page
    - No errors or alers were returned when passing through the offical Lighthouse tool.
    IMAGE
- classical facts
    - No errors or alers were returned when passing through the offical Lighthouse tool.
    IMAGE
- about me 
    - No errors or alers were returned when passing through the offical Lighthouse tool.
    IMAGE
- let's talk
    - No errors or alers were returned when passing through the offical Lighthouse tool.
    IMAGE

###Unfixed Bugs
You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

Hero image and heading are not in sync size-wise at certain media break points. I’ve not found a solution at this point.

Music Styles I like in let’s talk don’t always keep label with checkbox (when certain media point hits during wrapping).

Submit button has weird background color I can’t figure out.

Checkbox had initially multiple options that were reduced because of wrapping issued that could not be resolved within html and css technolgoies (that I could find).

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)
•	The site was deployed to GitHub pages. The steps to deploy are as follows:
o	In the GitHub repository, navigate to the Settings tab
o	From the source section drop-down menu, select the Master Branch
o	Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html

## Credits
In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.
You can break the credits section up into Content and Media, depending on what you have included in your project.
Content
•	The text for the Home page was taken from Wikipedia Article A
•	Instructions on how to implement form validation on the Sign Up page was taken from Specific YouTube Tutorial
•	The icons in the footer were taken from Font Awesome

## Media
•	The photos used on the home and sign up page are from This Open Source site
•	The images used for the gallery page were taken from this other open source site
Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!

## Other General Project Advice
Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work!
•	One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through this article by Chris Beams on How to Write a Git Commit Message
o	Make sure to keep the messages in the imperative mood
•	When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
o	For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept.
•	Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
o	Writing Your Best Code
o	HTML & CSS Coding Best Practices
o	Google HTML/CSS Style Guide
Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process!
