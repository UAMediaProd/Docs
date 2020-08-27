<h1 align='center'><img src="pantsss.png" width="130px"/><br/> Media Production</h1>

  
[About](#about)  
[Dev stack](#dev-stack)  
[Why the pants?](#why-the-pants)  
  
## About
The Media Production team at The University of Adelaide is located within the Online Programs Team (OPT) and acts as a central service inside the University. As the team has evolved from AdelaideX to Online Programs, so too has the desire to formalise an Open Source environment to work from and allow for future growth into adopting a [Serverless](https://serverless.css-tricks.com/) philosophy to allow design and development teams to focus on making content and using tools with GitHub. 

## Dev stack
Right now, our development tech stack roughly looks like this:

<p align='center'><img src="devstack.svg"/><br/></p>

GitHub will be the heart of our development toolset for new creations from hereon out. The main benefit this gives us is being able to use [GitHub Pages](https://pages.github.com/) in our DevOps for hosting rather than our previous closed-source approach to our own servers for front-end content. Using GitHub allows us to integrate with other services like [Glitch](https://glitch.com/) for Node.js server-side code for applications inside the Media team, or our future **Media Hub** project.

We still plan on supporting our GitLab instance for the time being until we migrate our previous projects to GitHub as we work on them. However, the existing files on our [SQL, Web and Python servers] (https://lti-adx.adelaide.edu.au/course-units/all/) will remain as we are currently unsure how far they have been re-used within the University and will maintain those servers for the legacy projects for MyUni projects *only* and for applications requiring Python and SQL databases.

### A note on GitLab
Future plans are to investigate the ownership of our current `BATS` and `WILD` servers and to include a Node.js installation there and only require our server for server-only tasks so we're Serverless-ish at the bare minimum.

## Why the pants?
Why not?
