# All Tax Back

## Overview
One Niche that I plan on targeting as a web developer is tax agents. For this reason I based this project off of alltaxback.ie. I redesigned 3 pages from this website (homepage, tax-refunds-rent-relief and apply-online). The idea behind this is to add to this project as I learn more skills from the Code Institute. Once the project is finished I will have a sample tax agent website. This will then be easy enough to slightly modify for when I get my first client.

## UX
The UX of this website is designed so that there is an obvious flow to guide the user through the website.

The flow of the website for a user who is interested in getting a tax refund is as follows.
1. Hero section - This is a full screen section which displays the compnaies logo and tagline. There is the an accreditation added to build an immediate sense of trust for users of the site. They will know that this tax agent is fully certified and experienced.
2. About Section - The next section is to explain a bit about the tax agent. As potential clients will be working with a single individual they will like to know a bit about that person. This also helps to build trust.
3. Services Section - This section explains the different services that the tax agent offers. This helps to explain to the visitor how the tax agent can help them.
4. Process Section - Now that we have built up trus and informed the user, we can show them how simple it is to get started with a 3 step process and a CTA to get them started.
5. Guarantee Section - If they are still not convinved at this point then we ease their minds with a No Refund No Feee guarantee and another CTA

The WireFrame for this project can be seen in the Wireframe Folder
The Style Guide is in the Style Guide folder

## Current Features
Feature 1 - build trust and authority by displaying experience, accrediatations and offering a guarantee.
Feature 2 - Display relevant information to the visitor so they know what is being offered.
Feature 3 - Display the simplicity of signing up.
Feature 4 - allows users apply to the service by filling out the contact form

## Features Left to Implement
* A digital signature is usually needed by tax agents to sign off on documents on the clients behalf
* Get an SSL cert so that clients information will be secure when being submitted

## Technologies Used
* Bootstrap https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css - this was used as it offers great ease of use and mobile responsiveness
* Fontawesome https://kit.fontawesome.com/6cb8961edb.js - this was used to add icons to the site
* JQuery & Javascript https://code.jquery.com/jquery-3.4.1.slim.min.js & https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js - this was used to add the * clickable dropdown menu in the menu bar
* HTML & CSS - Used to develop and design the website.

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

## Testing
This website is a fairly static website and there is not much needed in the way of error testing.

### Resposiveness
Use the chrome Inspect tool to evaluate the website at different screen sizes. The website scales correctly for all devices.

### Contact Form
Was informed that the contact form did not need to be functional as we have yet to cover JQeury & Javascript so no error testing here.

Didn't have any bugs occur but had issues trying to achieve certain results as it seemed like the styles were not being applied. This was generally down to bootstraps styles taking precedence or an inline-style that I had forgotten I added. The were solved using the chrome inspect tool.

### Deployment
1. Create a new repository called jakejamesreid.github.io
2. Create a new folder called "Deployment" and clone the new repo using git clone https://github.com/jakejamesreid/jakejamesreid.github.io
3. Navigate to the directory cd jakejamesreid.github.io
4. Copy and paste the website file into here
5. Add all files to staging area git add .
6. Commit the file git commit -m "Website Deployed"
7. Push the changes git push -u origin master

## Credits

### Content
All of the text for the services, process and guarantee sections and the text for the tax-refunds-rent-relief page was taken from https://alltaxback.ie/

### Media
The photos used in this site were obtained from https://elements.envato.com/, https://www.twenty20.com/ and https://www.irishtaxrebates.ie/

### Inspiration
The design for the contact form was taken from https://alltaxback.ie/apply-online/
The design for the blurbs in the services section and the tax-refunds-rent-relief page was taken from https://bbbootstrap.com/snippets/our-service-section-font-awesome-icons-49354397
The design for the navigation bar was taken from the Whiskey Drop code we done at Code Institute https://github.com/Jakejamesreid/Whiskey-Drop-Bootstrap
The design for the Hero Section was taken from https://codetheweb.blog/2017/12/07/fullscreen-image-hero/
The design for the footer was taken from https://mdbootstrap.com/docs/jquery/navigation/footer/
The design for the guarantee section was taken from https://alltaxback.ie/