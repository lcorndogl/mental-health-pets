 Mental Health and Pets

## [Link to Live Site](https://lcorndogl.github.io/mental-health-pets/)

## Contents

## Introduction

Mental Health has become an issue that has some stigma attached to it, however with people now talking about it and the impacts that it can have on daily living, this project aims to highlight some of the things that pets can help with when dealing with mental health issues.

## Responsivity Image
>
> Insert image of responsivity on multiple devices here

## User Experience

### stories

### Strategy

### Scope

### Structure

### Wireframes

#### Homepage

![Homepage Wireframe](docs/wf-home.png "Mental Health Pets Homepage Wireframe")

#### Gallery

![Gallery Wireframe](docs/wf-gallery.png "Mental Health Pets Gallery Wireframe")

#### Mobile / Tablet / Desktop breakpoints

### Surface

## Design

### Colour Scheme

The colour scheme has been chosen with the familiar colours of the NHS in the UK in mind, this is instill a consistency with the user expectations of other health services

[Coolors for the colour scheme](https://coolors.co/ebebeb-c2b8b2-197bbd-090c9b-2a2b2a)

![colour scheme](docs/colour-scheme.png "Mental Health Pets Colour Scheme")

### Imagery

The imagery used in this project has been taken by myself and my experiences owning my own pet.

### Typography

The typography used has been selected from Google Fonts, searching using the 'calm' filter, as a little addage to people who may be suffering with mental health and looking for information, as to not be an agressive font which could cause further issues in extreme cases

## Website Features

### Homepage

### About

### Gallery

### Get Help

## Future Features

Add custom domain to project to make it available at "<https://mhp.michaelcornall.co.uk>" with an SSL certificate

## Technologies Used

### HTML

Basic HTML is used to create the information to be displayed in the pages, links and other general website functions

### CSS

CSS is used to allow the formatting of the website, making it responsive and intuitive for the user to use

### Git

Git has been used to create versioning for the site as it is developed.

### GitHub

GitHub has been used as the central respository where the code will be accessible online. It has also been used to deploy the website to allow for testing throughout the development process as well as a location for the project to be visible to all

### Visual Studio Code

Visual Studio Code has been used to create the project as a pseudo-IDE, allowing for the use of emmet commands to help create the code in an efficient manner, as well as CoPilot integration

### CoPilot

CoPilot has been used as the AI tool in this project, utilising it for both helping with code creation such as pulling bootstrap templates into the code rather than using a search engine and the documentation where possible. It has also been used to help troubleshoot any errors within the code, and helping with getting the layout of the project correct in places where I may have struggled without it

### bash terminal

Bash Terminal used for adding and commiting files to the git repository, providing versioning as well as pushing these files to GitHub as a centralised location and deployment

## Deployment

1) Add the required files to the git repository with the command `git add .`
2) Commit the changes to the repository with the command commit command `git commit -m "Final project commit"`
3) Open up the repository and go to the settings > pages menu ([Mental Health Pets GitHub pages link](https://github.com/lcorndogl/mental-health-pets/settings/pages))
4) Select the root directory and main branch to deploy the project ![Deploy Settings for Project](docs/github-deploy-settings.png "GitHub Pages Deployment Settings")
5) Verify that the project has been deployed by going to the main repository page (Code) and checking the deployment status on the right hand side
[Link to Deployed Site](https://github.com/lcorndogl/mental-health-pets/settings/pages)
![Deployed Project Check](docs/github-deployed.png "GitHub Pages Deployment Check")

## Testing

### Insert tests here

### Lighthouse Audits

## Bugs

### CoPilot not importing bootstrap correctly

images in docs/bug1 folder

## Credits

### [Bootstrap](https://www.getbootstrap.com) - [Version 5.3.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

### CodeInstitute

Javascript code used to collapse navbar when a link is clicked

```javascript
<script>
    document
        .querySelectorAll(".navbar-collapse .nav-link")
        .forEach((link) => {
            link.addEventListener("click", function (e) {
                let section = document.querySelector(e.target.getAttribute("href"));
                if (section) {
                    e.preventDefault(); // Prevent default anchor click behavior
                    let navbarHeight = document.querySelector(".navbar-toggler").offsetHeight;
                    window.scroll({
                        top: section.offsetTop - navbarHeight, // Adjust for navbar height
                        behavior: "smooth",
                    });
                    document
                        .querySelector(".navbar-collapse")
                        .classList.remove("show"); // Collapse navbar
                }
            });
        });
</script>
```

### [Coolors for the colour scheme](https://coolors.co/ebebeb-c2b8b2-197bbd-090c9b-2a2b2a)

### [Mental Health Foundation (Various information on pets)](https://www.mentalhealth.org.uk/explore-mental-health/a-z-topics/pets-and-mental-health#:~:text=The%20companionship%20of%20a%20pet,you%20feel%20isolated%20or%20misunderstood)

### [Mind.org.uk - Support line help](https://www.mind.org.uk/information-support/guides-to-support-and-services/seeking-help-for-a-mental-health-problem/mental-health-helplines/)

### [NHS urgent help for mental health](https://www.nhs.uk/nhs-services/mental-health-services/where-to-get-urgent-help-for-mental-health/)

### [NHS - Information on some mental health problems](https://www.nhs.uk/nhs-services/mental-health-services/)

### [Stack Overflow - Undo Git Commit](https://stackoverflow.com/questions/927358/how-do-i-undo-the-most-recent-local-commits-in-git)

### [CloudConvert - Convert images to webp format](https://cloudconvert.com/jpg-to-webp)

### Fonts

#### [Agdasima](https://fonts.google.com/specimen/Agdasima?categoryFilters=Feeling:%2FExpressive%2FCalm)

#### [Quicksand](https://fonts.google.com/specimen/Quicksand?categoryFilters=Feeling:%2FExpressive%2FCalm)

#### [Sour Gummy](https://fonts.google.com/specimen/Sour+Gummy)
