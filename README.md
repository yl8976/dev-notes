# Developer Notes

These are notes to remind myself on my workflow all in one place.

## Terminal/iTerm

- Shortcuts are stored in the `~/.bash_profile` text file
- `lazygit` takes 1 argument (the commit description), and pushes it automatically to the `master` branch
- If you ever add new functions, refresh it by running `source ~/.bash_profile`
- `ctrl+U` clears the current line
- `cmd+K` clears the window
- `cmd+shift+K` clears the window **and** history above it

## Sublime Text

- Emmet

- ``control-'`` — toggle console

- `cmd+shift+c` — colour picker

- `cmd+alt+a` — align colons (for CSS/SASS)

- `ctrl+alt+c` — view file in Chrome

- `ctrl+alt+s` — view file in Safari

- `ctrl+alt+i` — view file in IE

- `ctrl+alt+f` — view file in FireFox

- `cmd+shift+p` — Open Command Palette:

  - `ChangeQuotes` changes quotes between " and '
  - `Git` opens git commands
  - `Emoji` inserts emojis you search up
  - `DA UI` makes the Sublime Text UI beautiful
  - `Colorsublime` adjusts themes and previews them in real time




## Languages

### JavaScript

### Python

### PHP

### HTML

### CSS

### Rust

- Sponsored by Mozilla
- Functional and imperative-procedural
- Syntax similar to C++
- Most loved language on Stack Overflow (2016-18)
- Projects
  - Firefox
  - Tor

### F# # 





### .NET

- Microsoft

### COBOL

- Old, used in business

### [ReasonML](http://reasonmlhub.com/exploring-reasonml/ch_about-reasonml.html)

- JS in OCaml syntax

## Libraries, Frameworks, Paradigms

### Workflows

[Agile Software Development](https://en.wikipedia.org/wiki/Agile_software_development)

- Scrum
- Kanban

### Front-End Development

[Front-End Frameworks/Libraries](http://voidcanvas.com/angular-vs-react-vs-ember-vs-vue-js/)

- React
  - Supported by Facebook
  - Library, not framework
    - Hard to setup because you have to pick components
  - Flux framework
    - Better than MVC
  - No official CLI
  - Huge JS/React community
  - JSX (basically JS + HTML)
  - React Native for mobile
- Angular
  - Supported by Google
  - Framework, not library
  - MVC framework
  - Easier to get started
  - Oldest framework; biggest community
  - TypeScript
  - Ionic for mobile
- Vue
  - New framework
  - Quickly gaining popularity
    - More stars on GitHub than Angular
  - Flux framework
  - Can't inherit components, have to use mixins always
  - "Easier than Angular"
  - Alibaba biggest consumer
  - Big community though not all are English-speaking
  - .vue extension, more a combo of HTML/CSS/JS
  - Weex(?) for mobile
- Ember
  - Older
  - Not as popular
  - Convention over configuration
    - i.e. have to spend lots of time learning conventions
  - LinkedIn completely on Ember
  - Small community
  - Pure JS
  - Cordova for mobile

[MVC/Flux](http://voidcanvas.com/flux-vs-mvc/)

- MVC
  - Old and trusted
  - 3 components: model, view, and controller
- Flux
  - New and promising
  - Action driven
  - Supported by Facebook



Polyfills

- [HTML5 Shiv](https://github.com/aFarkas/html5shiv/)
  - Workaround for styling HTML5 elements in IE prior to version 9
- [Modernizr](https://github.com/Modernizr/Modernizr)
  - Detects and implements workarounds/avoids using HTML5/CSS3 features based on browser

### Mobile Development

Xamarin

- Microsoft subsidiary
- C# codebase
- Native Android/iOS/Windows apps

[Apache Cordova](https://cordova.apache.org/docs/en/latest/guide/overview/)

- Used to be PhoneGap, now open-source
- HTML/CSS/JS for native mobile apps

### Testing, Integration, Deployment, Delivery

[Continuous Integration/Continuous Delivery (CI/CD) Tools](https://blog.takipi.com/jenkins-vs-travis-ci-vs-circle-ci-vs-teamcity-vs-codeship-vs-gitlab-ci-vs-bamboo/)

- [CI and CD](https://www.atlassian.com/continuous-delivery/ci-vs-ci-vs-cd)
  - To put it simply continuous integration is part of both continuous delivery and continuous deployment. And continuous deployment is like continuous delivery, except that releases happen automatically.
  - CI
    - Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.
    - Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.
  - CD
    - Delivery: [Continuous delivery](https://www.atlassian.com/continuous-delivery) is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button.
      - In theory, with continuous delivery, you can decide to release daily, weekly, fortnightly, or whatever suits your business requirements. However, if you truly want to get the benefits of continuous delivery, you should deploy to production as early as possible to make sure that you release small batches, that are easy to troubleshoot in case of a problem.
    - Deployment: Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.
      - Continuous deployment is an excellent way to accelerate the feedback loop with your customers and take pressure off the team as there isn't a *Release Day* anymore. Developers can focus on building software, and they see their work go live minutes after they've finished working on it.

CI/CD Tools

- Jenkins
  - Most well-known
  - Free and open-source
- Travis CI
  - More CI than CD
  - Free for open-source
- TeamCity
  - Made by JetBrains
  - Free professional license (100 build configs, full features)
- CircleCI
  - Good on VC (GitHub/Bitbucket etc.)
  - Auto-cancel redundant builds on GitHub
- Codeship
  - Pro version uses Docker
  - Free plan (100 builts per month for unlimited projects/users/teams)
  - [Public collection of utilities](https://github.com/codeship-library)
- GitLab CI
  - Free with GitLab (Community Edition)
  - Open-source
- Bamboo
  - Made by Atlassian
    - Good integrations with their other products (e.g. JIRA/Bitbucket)
  - Pay per "agent," no free plan



## CS Concepts

### Algorithms

Randomized Algorithms

- Las Vegas Algorithm
  - Correct but only probably fast
- Monte Carlo Algorithm
  - Fast but only probably correct
- Atlantic City Algorithm
  - Bounded probabilistic polytime that are probably correct and probably fast
  - Correct at least 75% of the time (or in some versions 50%)