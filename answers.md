### Prompt 1

- Describe in detail the favorite feature that you built, designed or delivered as a member of your project team.
    - **Please include links to a Figma file, pull-requests or link to a file in a repository that outlines the work you did on this feature.**

  My favorite feature to build out for this project was the custom email activation request on registration which sent a customized HTML markedup email to the registree while also
integrate with Okta's registration flow path. All of the files involved in the execution of this feature can be found on the Back End repository for our team. The feature needed
multiple systems set up to work. I had to use Node's FS service to read and write html files with unique names (built from hashes) to and from the server's OS's temp directory.
I also used the nodemailer NPM package to send the email to the end-user. All in all it was super interesting.

- Describe the biggest hurdle you overcame technically or from a design perspective.
    - **Be specific in what the problem was and how you overcame it.**

  Setting up Multifactor authentication with Okta was my biggest hurtle, the Okta website is documented in a less then straighforward manner (some parts of the documentation being
literally broken) Some solutions I had to intuit whilst others took many hours and days of searching in order to solve. This was especially so because I chose the most secure 
type of authentication (PCKE Multifactor) 

- Describe in detail the biggest 'inter-personal' conflict you overcame as a member of your project team.
    - **Be specific but please don't mention any team members by name.**

As a team I felt we were very strong and I have had no outstanding issues with any member of it 

