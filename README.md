# Hackero Webpagebuilder
This project makes it easy to build a hackero.io webpage!
It can be used to build Hackero webpages for the [NPC Competition](https://blog.hackero.io/npc-competition/)

## Competition
Create your own NPC that will be part of the game! Everything you need to know is a little bit of development skills in html and css (less).
### Participation
To Participate fork this project.
When you are finished commit your changes and and merge your fork with this repository!
### Rules
- Webpages should stay small and compact. They can be more complex (e.g. bjoernhub) or really easy (anysoft).
- Do not infringe trademarks of other companies or people in any way!
- Everything you create must be usable for free!
- Logos you create for companies must be created by yourself!
- Your webpage should be suitable for minors!
- No Javascript is allowed inside the webpages!

We will exclude everyone from the competition who will not follow these rules! Excluded webpages will not take part in the competition.

### Procedure
Submissions will be accepted till the 18th of August 2019. After that day the community will be able to vote on their favourite Design. This design will be implemented into the game  as a npc!
## Setup
### Requirements
- Node.js (>= 10.x.x)
### Setup
1. Go into the root directory of the cloned project.
2. Open a Terminal and run `npm install`.
3. Wait for it to finish!
4. Navigate to the `pages` folder inside the project. Rename the `template` folder to the name of your company!
5. Run the watcher via `npm run watch`.
6. You can now open your webpage by opening the `index.html` file inside your **renamed** `template` folder.
7. Change the files as you desire!
8. Complete the COMPANY_README.md file!
9. When you are ready commit the changes back to github and merge your fork with this project.
### Inspiration
There are two pages (anysoft and bjoernhub) as an inspiration. Please do not change them!

### Folder structure:
```
webpage-builder/
├── build/... (Build files will be placed here)
├── escaped/... (Build files will be placed here)
└── pages/
    ├── anysoft
    │   ├── brands/
    │   │   └── anysoft.png
    │   ├── index.html
    │   ├── style.less
    │   └── style.css
    ├── bjoernhub
    │   ├── brands/
    │   │   └── bjoernjub.png
    │   ├── img/  
    │   │   └── bjoern1.jpg
    │   │   ⋮
    │   ├── index.html
    │   ├── style.less
    │   └── style.css
    └── template
        ├── brands/         ---- logo
        │   └── template.png
        ├── img/            ---- Other images
        ├── index.html      ---- Edit html here
        ├── style.less      ---- Edit css / less here
        ├── COMPANY_README.md       ---- Further info about your page
        └── style.css       ---- automatically generated (Do not edit manually!)
```

###  Important
- Your logo should be named after the companies name
- Only logo goes into brands folder. everything else goes into img folder!
- Never edit style.css as it is overwritten, by edits!
- Do not forget to edit your COMPANY_README.md