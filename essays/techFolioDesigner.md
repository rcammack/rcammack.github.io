---
layout: essay
type: essay
title: "TechFolio Designer Onboarding"
date: 2018-08-24
labels:
  - Electron
  - TechFolio
  - Desktop App
---
### Background- 

This essay is here, on my portfolio website, because I added a Markdown file to my TechFolio (the ship name of technical and portfolio) repository. This repo was initially a template forked from [TechFolios](https://github.com/techfolios/template) which I customized for ICS 314 (Software Engineering) in Spring 2018. Now, in the Fall 2018 ICS 491 course, I will be exchanging editing my files in code editors for editing my files in [TechFolio Designer](https://github.com/techfolios/techfoliodesigner), the desktop application specifically designed to help people edit their TechFolio in a more user-friendly way. 

### My experience onboarding as a TechFolio Designer (TFD) developer-

My initial reaction when opening TFD was that I was excited to learn more about designing a desktop application and, in particular, how [Electron](https://electronjs.org/) could help make that happen. A quick Google search of Electron, an open-source framework for creating desktop applications, reveals its success through the creation of apps such as Skype, Atom, GitHub Desktop, and more. Helping with the development of an app that was implemented using Electron, such as the TFD, can help me learn how cross-platform desktop applications are designed. 

After experimenting with TFD, I discovered many significant flaws in the application. The first inconvenience I encountered was that I had to re-clone my TechFolio. There was no option for me to simply point the application towards the correct local repo I had previously cloned from GitHub. Then, I was unhappy to find that I could not copy and paste in the TFD editors. I also expected there to be a preview for markdown files like on GitHub and in IntelliJ IDEA. Another feature that I expected was a way to browse for an image to upload and a way to crop it into the required square format, sort of like how social media profile image uploads work. In addition, a "new" or "+" button to add a new Activity, Work, etc. seems intuitive, and it would also be nice to be able to leave a commit message in the app. 

The biggest issue, however, is that editing the bio.json file using the Simple Bio Editor in TFD can cause data originally in the file to be deleted. My bio.json file, which I had already filled out, contains data not shown in the editor, and when I saved the changes made in the editor, I noticed in GitHub Desktop that there were additional deletions in my file. For example, saving any changes to the Skills tab would delete any keywords for a skill that came after the first 3 shown in the editor. As a developer, I would focus on fixing this bug first to improve TFD. 

Despite these issues, I realize how TFD could help people with minimal technical skills edit their own TechFolios. Personally, I never had a problem editing the biography information in the JSON file, but I know that others had problems with the syntax, which the Simple Bio Editor helps resolve. The main problem I had with my TechFolio in Fall 2018 was with not catching spelling errors before I pushed my essays and projects to master. Hopefully, that issue can be solved for users in the future through the use of TFD. 
