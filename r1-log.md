# 100 Days Of Code - Log - Round 1 - Michael Hettmer

The log of my [#100DaysOfCode](https://twitter.com/search?q=%23100DaysOfCode) challenge. Started on February 4, Tuesday, 2020.

## R1D001 - February 4, Tuesday, 2020

- Finished my plan for this challenge in this repository
- Started to build a LaTeX starter template on GitHub with a fully configured CI/CD Workflow

Tweet: https://twitter.com/MichaelHettmer/status/1224829842094542848?s=20

## R1D002 - February 5, Wednesday, 2020

- Started an OpenSource project. It will be a collection of useful LaTeX tools I need myself including CI/CD templates. 
- It was fun playing around with RenovateBot, the NPM registry, SemanticRelease and GitHub overall.
- Releases are now fully automated including a changelog generation.


Tweet: https://twitter.com/MichaelHettmer/status/1225185412836155392
Project: https://github.com/MichaelHettmer/latex-toolkit

## R1D003 - February 6, Thursday, 2020

- Made some progress on latex-toolkit. Mostly building the base for the CLI functionality.
- Until now all the code was written [test-driven](https://en.wikipedia.org/wiki/Test-driven_development) as much as possible.
- Learned a lot about Yeoman, Yargs and InquirerJS.
- Gonna build some configurable templates tomorrow.


Tweet: https://twitter.com/MichaelHettmer/status/1225553331969568771<br/>
Project: https://github.com/MichaelHettmer/latex-toolkit

## R1D004 - February 7, Friday, 2020

- I have created a package for all my @yeoman generators and templates. Will save me a lot of time future.
- First time I tried a Pomodoro-based time tracker app. Turned out this is indeed a great way to stay focused. Didn't get lost in the rabbit hole today.
- Tomorrow I will concentrate much more on the actual cli code. Infrastructure setup is finally completed 🤖

Tweet: https://twitter.com/MichaelHettmer/status/1225813771387625475<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D005 - February 8, Saturday, 2020

- Got lost in improving the infrastructure and build tools again. Too much automation. I guess my code doesn't need me anymore 😀
- I also added a first actual template and the required copying logic. That part was quite tricky but I got it working 🎉

Tweet: https://twitter.com/MichaelHettmer/status/1226308424322953216<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D006 - February 9, Sunday, 2020

- Had to meet an important deadline today so couldn't get much done here ⏱️
- Nevertheless I worked a small night shift to add a master generator which can be used as a launcher for all available @yeoman subgenerators
- All subgenerators are presented as an interactive list which the user can choose one generator from
- The chosen generator is started as a subprocess afterwards
- Now the user doesn't have to know which generators are included and can easily select one from a nice list 🧒

Tweet: https://twitter.com/MichaelHettmer/status/1226680736834637824<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D007 - February 10, Monday, 2020

- Another late shift today 🌙
- But I finally have some running code to show, see GIF in linked tweet below.
- This is generating a starter template for developing a Docker image with an automated build and release setup.

Tweet: https://twitter.com/MichaelHettmer/status/1227073629936128000<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D008 - February 11, Tuesday, 2020

- Nothing spectacular new today.
- Fought some config files for hours 👿 CircleCI didn't like me today.
- Finally my generator truly generates a new project. Including a brand new GitHub repository and a CircleCI project.

Tweet: https://twitter.com/MichaelHettmer/status/1227391862304116736<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D009 - February 12, Wednesday, 2020

- Played around a lot with @Docker and @gatsbyjs today.
- Used my template generator to publish a small utility Docker image for building GatsbyJS projects in a CI.
- Template generator works great. It doesn't even take a minute until a new OpenSource project is setup including CI/CD.

Tweet: https://twitter.com/MichaelHettmer/status/1227748468845883394<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D010 - February 13, Thursday, 2020

- A lot of @yeoman generator refactoring today.
- Extracted code into base modules so that I can reuse them later.
- Learned some new things about TypeScript generics while doing that.

Tweet: https://twitter.com/MichaelHettmer/status/1228109667978575872<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D011 - February 14, Friday, 2020

- Wrote some unit and integration tests with Jest today.
- Making sure those automated dependency upgrades won't break anything.
- Learned a lot from @kentcdodds's blog about testing and best practices.

Tweet: https://twitter.com/MichaelHettmer/status/1228489884689747973<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D012 - February 15, Saturday, 2020

- Did not have as much time today as planned.
- Created another template for #nodejs libraries and applications.
- Tomorrow I'll create a @gatsbyjs template based on it which will come in very handy when I build my portfolio / blog as the final R1 project.

Tweet: https://twitter.com/MichaelHettmer/status/1228881650383237122<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D013 - February 16, Sunday, 2020

- A lot of bugfixes and small improvements today.
- No this is not the release notes section of every app I have on my phone 😀
- Seriously made my template generator much more bulletproof and added new cli options to skip some steps e.g. while testing.

Tweet: https://twitter.com/MichaelHettmer/status/1229155478036455425<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D014 - February 17, Monday, 2020

- Wrote a lot of unit tests.
- Making the generator rock solid.
- Started the promised gatsby template which will be divided in an app, a plugin and a theme template.

Tweet: https://twitter.com/MichaelHettmer/status/1229556533249355776<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D015 - February 18, Tuesday, 2020

- Did a lot of experimenting with GatsbyJS and Expo today.
- And at this point I'm not sure anymore if I really want to build my portfolio as a website. React Native Web has improved a lot and real websites on mobile still feel like... well websites 😅
- Of course this highly depends on the use case. But it's kind of funny how React Native emerged out of React as a native companion and now it is able to target web itself, making it the one tool to rule them all.

Tweet: https://twitter.com/MichaelHettmer/status/1229921899070869505

## R1D016 - February 19, Wednesday, 2020

- Business trip today and I'm soo tired. No time to code but I don't want to miss a post so at least there was a twitter post 🙃
- I'll be working extra hard the next days to compensate! Learned a lot about privacy and scalability of blockchain applications though.
- A few more templates to go and then I'll start my portfolio website / blog development

Tweet: https://twitter.com/MichaelHettmer/status/1230283209851666433

## R1D017 - February 20, Thursday, 2020

- Almost finished multiple Gatsby templates today for theme, plugin and website development.
- Will continue tomorrow. Still tired 😀

Tweet: https://twitter.com/MichaelHettmer/status/1230615882822377473<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D018 - February 21, Friday, 2020

- No post yesterday. One week into my new job and it's already hard to keep up.
- BUT I actually prepared two more templates for the generator, so still got something done.
- Hopefully I'll finish it today so I can move on to building my website.

Tweet: https://twitter.com/MichaelHettmer/status/123116663553023590<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D019 - February 22, Saturday, 2020

- Played a lot with Expo today.
- Added i18n and a very basic offline-first approach to a small demo app.
- It really is more important to think about perceived than measured performance. And a good offline caching strategy is part of it.

Tweet: https://twitter.com/MichaelHettmer/status/1231375884441006082<br/>

## R1D020 - February 23, Sunday, 2020

- A huge step forward with my generator application.
- Gatsby template can now reuse node template.
- Tests are all working now even if generators are nested.

Tweet: https://twitter.com/MichaelHettmer/status/1231759469622763521<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D021 - February 24, Monday, 2020

- Worked on a React Native sideproject today.
- Made progress simplifying its offline first state management with a hell of a lot TypeScript clutter abstracted away into separate modules.
- This could become a cool little library
- My new mission for tomorrow!
- Also fixed some bugs in the generator application

Tweet: https://twitter.com/MichaelHettmer/status/1232076756443594752<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D022 - February 25, Tuesday, 2020

- Finished the template generator gatsby update and made a new release.
- Publishing everything immediately on #npm and #GitHub is probably the best practice i've adopted so far while doing this challenge.
- Forces you to write better code and documentation.

Tweet: https://twitter.com/MichaelHettmer/status/1232472309031587845<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D023 - February 26, Wednesday, 2020

- Today I built the infrastructure for selfhosting my portfolio.
- Works really well. Hosting and auto deployment for each push on master is enabled.
- The only thing that is missing now is the actual website 😅

Tweet: https://twitter.com/MichaelHettmer/status/1232843165239054336<br/>
Project: https://github.com/MichaelHettmer/website

## R1D024 - February 27, Thursday, 2020

- Fixes
- Documentation and Readme updates
- Sleep! :D Had a tough day at work so just a small update today

Tweet: https://twitter.com/MichaelHettmer/status/1233158116386246659<br/>
Project: https://github.com/MichaelHettmer/generator-mht

## R1D025 - February 28, Friday, 2020

- Docker research day
- Learned about multistage builds
- Will update my gatsby development container to be a hosting container as well
- Awesome feature

Tweet: https://twitter.com/MichaelHettmer/status/1233523118079139840

## R1D026 - February 29, Saturday, 2020

- Tried to start a website with my template generator
- Found a few bugs in it and got lost fixing them
- Will start my website another day when the gatsby template is working

Tweet: https://twitter.com/MichaelHettmer/status/1233909129946767361<br/>
Project: https://github.com/MichaelHettmer/website

## R1D027 - March 1, Sunday, 2020

- Free day. At least that is what sundays are for right?
- Read one or two new things about docker.
- Thought about possible layouts for my website.

Tweet: https://twitter.com/MichaelHettmer/status/1234263696794406914

## R1D028 - March 2, Monday, 2020

- I have started building my personal website by designing a simple start page.
- The most difficult part for me is certainly deciding on the color theme and layout.
- So many different ideas. We'll see how that turns out in the end.

Tweet: https://twitter.com/MichaelHettmer/status/1234639210705031168?s=20<br/>
Project: https://github.com/MichaelHettmer/website