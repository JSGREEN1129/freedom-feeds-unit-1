# [freedom-feeds-unit-1](https://jsgreen1129.github.io/freedom-feeds-unit-1)

Developer: Josh Green ([JSGREEN1129](https://www.github.com/JSGREEN1129))

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/JSGREEN1129/freedom-feeds-unit-1)](https://www.github.com/JSGREEN1129/freedom-feeds-unit-1/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/JSGREEN1129/freedom-feeds-unit-1)](https://www.github.com/JSGREEN1129/freedom-feeds-unit-1/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/JSGREEN1129/freedom-feeds-unit-1)](https://www.github.com/JSGREEN1129/freedom-feeds-unit-1)

Freedom-feeds is a charity that engages in fundraising activites to help support war veterans and their families, when they suffer hardship due to military deployment. This can be in the form of members of the public and corporate companies donating food, everyday essentials and technology grants. The freedom-feeds website will give users information on the charity itself, details on how users can contribute and donate to support the charity, contact details for the charity and information on how donations are used.


**Site Mockups**
![Site Mockups](./documentation/freedom-feeds-responsive.png)

source: [freedom-feeds-unit-1 amiresponsive](https://ui.dev/amiresponsive?url=https://jsgreen1129.github.io/freedom-feeds-unit-1)

## UX

### The 5 Planes of UX

#### 1. Strategy

**Purpose**
- Encourage users to donate to freedom-feeds by showcasing their mission, community and how donations are used.
- Provide a seamless user experience to keep users informed.

**Primary User Needs**
- Learn about the charity’s purpose and reasons.
- Learn how to donate to the charity.
- Access responsive and informative content.

**Business Goals**
- Increase donations.
- Boost awareness and create a recurring revenue.

#### 2. Scope

**[Features](#features)** (see below)

**Content Requirements**
- Clear, motivational text about the charities mission.
- Article of a war veterans family and their struggles.
- Contact form.
- External link to the salvation army.

#### 3. Structure

**Information Architecture**
- **Navigation Menu**:
  - Accessible links in the navbar.
- **Hierarchy**:
  - Clear call-to-action buttons.
  - Clear contact details.

**User Flow**
1. User lands on the home page → learns about the charity's mission and the people they help.
2. Navigates to the donate page → sees how they can donate.
3. Donate through one off donation or 12-month donation subscription.

#### 4. Skeleton

**[Wireframes](#wireframes)** (see below)

#### 5. Surface

**Visual Design Elements**
- **[Colours](#colour-scheme)** (see below)
- **[Typography](#typography)** (see below)

### Colour Scheme

- `#000000` Site background.
- `#FFFFFF` primary text.
- `#B22222` secondary text.

### Typography

    font-family: 'Poppins', sans-serif;
- [Poppins](https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap)
- [sans-serif]
- [Flaticon](https://www.flaticon.com/free-icons/poppy) icons were used throughout the site in navbar and the footer.

## Wireframes

Wireframes were developed for mobile and desktop sizes.
I've used [Wireframe](https://wireframe.cc/) to design my site wireframes.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](./documentation/homepage-mobile.png) | ![screenshot](./documentation/homepage-desktop.png) |
| Donate | ![screenshot](./documentation/donate-mobile.png) | ![screenshot](./documentation/donate-desktop.png) |
| Contact | ![screenshot](./documentation/contact-mobile.png) | ![screenshot](./documentation/contact-desktop.png) |

## User Stories

| Target | Expectation | Outcome | Proof |
| --- | --- | --- | --- |
| As a user | I would like to see reasons why I should donate to freedom-feeds | so that I can learn about the charity's mission and purpose before deciding to donate. | ![screenshot](./documentation/user-story-1-proof.png) |
| As a user | I would like to view information on how my donations would support war veterans and their families | so that I can decide whether to donate. | ![screenshot](./documentation/user-story-2-proof.png) |
| As a user | I would like to find the contact details for the charity | so that I can communicate and offer to volunteer my time. | ![screenshot](./documentation/user-story-3-proof.png) |
| As a user | I would like the website to be fully responsive | so that I can easily navigate and access information from my phone, tablet, or desktop. | [Responsiveness](https://github.com/JSGREEN1129/freedom-feeds-unit-1/blob/main/TESTING.md#responsiveness) |

## Features

### Existing Features

| Feature | Notes | Screenshot |
| --- | --- | --- |
| Navbar | Featured on all three pages, the full responsive navigation bar includes links to the Home page, Doante page and Contact page, and is identical in each page to allow for easy navigation. On the smallest screens, there are no poppy icons. This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the "back" button. | ![screenshot](./documentation/navbar-desktop.png) |
| Hero Image | All pages include a photo with text-overlay. | ![screenshot](./documentation/freedom-feeds-hero-image-donate-page.png) |
| Sophies Story | A personalised story form the wife of a war veteran whos husband suffered extreme mental health difficulties when returning from deployment. | ![screenshot](./documentation/freedom-feeds-sophies-story.png) |
| CTA Button | A purpose built CTA button which can be positioned throughout the website to guide visitors to the donations page. | ![screenshot](./documentation/freedom-feeds-cta-button.png) |
| Salvation Army external link | An external link which opens the salvation army website in a new tab by clicking the logo. | ![screenshot](./documentation/freedom-feeds-salvation-army.png) |
| Contact form | An easy to navigate contact form and submit button for users to contact through the web. | ![screenshot](./documentation/freedom-feeds-contact-form.png) |
| Footer | A basic footer which in the future could be enhanced to included social media links and a donations collected ticker. | ![screenshot](./documentation/footer-desktop.png) |

## Tools & Technologies

| Tool / Tech | Use |
| --- | --- |
| [![badge](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://markdown.2bn.dev) | Generate README and TESTING templates. |
| [![badge](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com) | Version control. (`git add`, `git commit`, `git push`) |
| [![badge](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com) | Secure online code storage. |
| [![badge](https://img.shields.io/badge/VSCode-grey?logo=htmx&logoColor=007ACC)](https://code.visualstudio.com) | Local IDE for development. |
| [![badge](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML) | Main site content and layout. |
| [![badge](https://img.shields.io/badge/CSS-grey?logo=css3&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS) | Design and layout. |
| [![badge](https://img.shields.io/badge/GitHub_Pages-grey?logo=githubpages&logoColor=222222)](https://pages.github.com) | Hosting the deployed front-end site. |
| [![badge](https://img.shields.io/badge/Font_Awesome-grey?logo=fontawesome&logoColor=528DD7)](https://fontawesome.com) | Icons. |
| [![badge](https://img.shields.io/badge/ChatGPT-grey?logo=openai&logoColor=75A99C)](https://chat.openai.com) | Help debug, troubleshoot, and explain things. |

## Testing

> [!NOTE]
> For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

### GitHub Pages

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://www.github.com/JSGREEN1129/freedom-feeds-unit-1), navigate to the "Settings" tab.
- In Settings, click on the "Pages" link from the menu on the left.
- From the "Build and deployment" section, click the drop-down called "Branch", and select the **main** branch, then click "Save".
- The page will be automatically refreshed with a detailed message display to indicate the successful deployment.
- Allow up to 5 minutes for the site to fully deploy.

The live link can be found on [GitHub Pages](https://jsgreen1129.github.io/freedom-feeds-unit-1).

### Local Development

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://www.github.com/JSGREEN1129/freedom-feeds-unit-1).
2. Locate and click on the green "Code" button at the very top, above the commits and files.
3. Select whether you prefer to clone using "HTTPS", "SSH", or "GitHub CLI", and click the "copy" button to copy the URL to your clipboard.
4. Open "Git Bash" or "Terminal".
5. Change the current working directory to the location where you want the cloned directory.
6. In your IDE Terminal, type the following command to clone the repository:
	- `git clone https://www.github.com/JSGREEN1129/freedom-feeds-unit-1.git`
7. Press "Enter" to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://www.github.com/JSGREEN1129/freedom-feeds-unit-1)

**Please Note**: in order to directly open the project in Gitpod, you should have the browser extension installed. A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, you make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository. You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://www.github.com/JSGREEN1129/freedom-feeds-unit-1).
2. At the top of the Repository, just below the "Settings" button on the menu, locate and click the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

There are no remaining major differences between the local version when compared to the deployed version online.

## Credits

External assistance used and image repositories

https://markdown.2bn.dev - Help generating Markdown files 

https://www.youtube.com/watch?v=gWgzzVVcqfA - For contact form

https://www.cleanpng.com/free/salvation-army.html - Salvation army PNG

https://unsplash.com/ - Images throughout website

https://www.pexels.com/ - Images throughout website

https://www.freepik.com/ - Images throughout website

https://www.flaticon.com/free-icons/poppy - Poppy icon used in header and footer

### Assistance acknowledments

Throughout my project I used sources to help me with the development and understanding of specifc elements of code that I struggled with. I used the below assistance. I mainly used the below for help with applying overlay to images in the hero section and also for mobile responsiveness.

https://www.w3schools.com/ - Help with code logic and explanations 

https://www.geeksforgeeks.org/ - Help with code logic and explanations 

https://chatgpt.com/ - Help with code logic and explanations 

### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://www.github.com/TravelTimN) for the support throughout the development of this project.
- I would like to thank the [Code Institute](https://codeinstitute.net) Tutor Team for their assistance with troubleshooting and debugging some project issues.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for the moral support; it kept me going during periods of self doubt and impostor syndrome.


