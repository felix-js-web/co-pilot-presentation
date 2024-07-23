# co-pilot-presentation
# Scaling with java MeetUp with Sasha Berezovska and Erik Pragt, Derek Bingham, Amazon Web Services (AWS), Lanson Partners
## Agenda. Coding Smarter, Not Harder - Leveraging GitHub Copilot for Java.

- make an intro about how it was before th copilot a little bit (Add an example of how excited you were to play it around.) (Lot of code, manual boilerplate, lomboks, projects half baked because too much manual work and no unit testing because no time, sprints executed only for 50% and still feeling of you can do so much more you just did not have enough time)(mention about senior level you want to do more concerns and principles which are critical - but you never have tim efor it - moreover your collagues might not share or see it like that and ask them to redo it on PR and etcs can not be a positive experience for sure cause everyone is tired.). (Mention that you thought may be there are some great resources which are explaining CoPilot in general and many which are explaning it usage with Code - but of course you looked for something which touches both crossroads.)  
- Introduction to GitHub Copilot – principles. (refer to PPTX file, mention Canva AI vs Microsoft Copilot and your own experience, mention the hardest was the PPT file - of course because you are en engineer). Switch to PPTX. Refer in models part to AWS https://aws.amazon.com/certification/certified-machine-learning-specialty/ foe stronger understanding of AI and LLM . An example of how your mind is being an LLM trained on your home data and if you asked any question like what do you have int he garage - do you have a GLue - do you have a ScrewDriver or whatever, similarly gitHub CoPilot trained on github data - thats simple as that.
- Numbers and feedback about CoPilot in tech community (Mention about resources and Ryan Salva VP of Product GitHub Copilot PO and his visit in Sydney) Accenture Video Link and results of customer 0 100k+ developers. Numbers.https://www.youtube.com/watch?v=AAT4zCfzsHI FYI Accenture makes it a must to use github copilot 
- Spring Boot project from scratch with CoPilot
   > Basic H2, CRUD, Web project

   > prompting and better context key to success

   > how to use the suggestions and refactor the code VCS help from CoPilot
  
- React project from scratch with CoPilot
- Future of AI Pair Programming
   > CoPilot workspaces
   > CoPilot plugins
   > CoPilot predictions
- Q&A


## General. About me.
A [repo](https://github.com/felix-js-web/co-pilot-presentation) for resources of the talk.
>
> Passionate Java coder - holding all current Java certifications. and multiple AWS certifications.
> Mostly spent my last 10+ years in Java EcoSystems and projects with Spring and Spring boot doing lot's of integrations
> Recently which is last 3+ years also enjoying Node.js and React.js. with TypeScript.
> if you have questions please feel free to reach me at felix.java.web@gmail.com or my linkedin profile.

### Abstract
TODO

resources and numbers

https://resources.github.com/learn/pathways/copilot/essentials/measuring-the-impact-of-github-copilot/

https://docs.sonarsource.com/sonarqube/latest/user-guide/concepts/#:~:text=soon%20as%20possible.-,Code%20smell,errors%20as%20they%20make%20changes.

https://docs.github.com/en/copilot/managing-copilot/managing-github-copilot-in-your-organization/reviewing-github-copilot-activity-in-your-organization/reviewing-usage-data-for-github-copilot-in-your-organization

https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/

https://cacm.acm.org/research/measuring-github-copilots-impact-on-productivity/

CoPilot Plugins
https://www.getrecall.ai/summary/github/extending-github-copilot-insights-from-atlassian-elastic-and-split
https://www.youtube.com/watch?v=JclDSHrSZV0&t=3s
### Outline

#### Overview
##### `Introduction to GitHub Copilot – principles`
- what it does and how it works
- what it does not 
- numbers and feedbacks from tech community

#### BackEnd
##### `building a basic CRUD APP`

______ KEY IDEA - every time I have a question? I ask copilot - hello google traffic -)   I ask copilot I ask copilot in 10 seconds I get an answer!! thats it
  -- trying to see if I can use copilot anyhow to build from scratch or anything -it did not help
  -- Asked itself it was asking me to do everything manually
  -- Used copilot then to start with 
  -- controller sample with mono and flux to test
  -- dto and entity classes
  --  create repository for JPA based on that
  --  then Called it from Controller directly through DI
  --  then Added H2 db properties to application.properties
  --  then need to generate postman collection for testing
  --  then generate swagger api yaml
  -- failed on docker image -( no java 21 in some hub) 
  -- but eventually succeded with temurin 21   https://hub.docker.com/_/eclipse-temurin
  -- building docker now about to start and started
  -- VCS - no comms from Intellij Copilot plugin - but youc an go to chat and ask to generate a commit message and ask it to be improved
  -- commit it please 
HOW DO BUSINESSES Identify number of commit by copilot??
  - like they give the number and say that much from it is from COPILOT

#### Frontent
##### `building a basic Call to localhost 8080 in VS code`
-- how did I start with create react app
-- how I asked it to synch with the repo and failed - will try to redo it as usual
-- clone and then ask react create app in the git copied folder similar to what happened in spring boot
-- start it and ask it to call localhost 8080
-- trying to make it multi component


#### Future of AI programming
##### `CoPilot workspaces and codespaces`
##### `CoPilot plugins`
-- 2 fantastic video resources of last is 4 days old one is above with Ryan Salva, and last one is a really really must see https://www.youtube.com/watch?v=JclDSHrSZV0
-- Describe the principle of LLM and AI now adding up to its currents the providers like Atlassian Elastic and etcs and make it more effective for us to.......
-- future is probably with many plugins which will source any information we need but 
##### `Predictions`

