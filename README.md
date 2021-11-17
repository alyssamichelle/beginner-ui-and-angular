# Beginner UI & Angular

For UI and Angular beginners alike. Let's pull down the Tour of Heroes app (found throughout the Angular docs) and give it a UI upgrade!
 

- Dive into the Tour of Heroes demo application like never before!
- Learn about integrating Sass into your Angular Project.
- Learn how to include a Component Library into your Project. (We will be using Kendo UI but the principles to implement a UI Library are pretty universal.)
- Play around with customizing styles and writing custom CSS from scratch.
- Go over UI/UX principles and implement them on the fly.
- Talk about some accessibility tips along the way.



----------
## UI Challenge

Learning often sticks best when combined with application. Why not take part in a UI Challenge during my talk, to try out some of the new techniques you’ll be learning throughout?!

I have 3 Amazon gift cards and a pair of Bose Headphones up for grabs, all you need to do is clone [this repo](https://github.com/alyssamichelle/angular-tour-of-heroes) and upgrade the UI! Bonus points for including Kendo UI Components. 

### How to Enter the UI Challenge
Tweet a screenshot of your upgraded UI and/or code with the tag #heykendoui to enter the competition! I'll reply to the winning tweets for contact info!


----------

## Getting Started - Tour the Tour of Heroes

- talk about GH vs StackBlitz
    - Clone down the GitHub Repo
    - → https://github.com/alyssamichelle/angular-tour-of-heroes
    - -or- open in StackBlitz and Fork!
    - → https://stackblitz.com/github/alyssamichelle/angular-tour-of-heroes
- Clone down the TOH
- Talk about Angular Basics: give a tour of the routes & components

### Angular Basics

- application structure 
- The CLI
- Routes 
- Modules (covered more later on kendo install)
- Components
- Templates
- Directives: used to modify the behavior, appearance, or structure (ngIf) of the DOM
- Data binding

- Sass variables & CSS Custom Properties
    - syntax differences
    - view encapsulation with :root for css vars
    - If you need to update a variable after view has been rendered, use CSS variables (Sass vars won’t exist anymore)


### Including Sass with a new project
    ng new my-scss-app --style=scss
    
### Including Sass in an existing project:
    ng config schematics.@schematics/angular:component.style scss

## Including Kendo UI
### The Card Component
[Card Component Docs](https://www.telerik.com/kendo-angular-ui-develop/components/layout/card/)

#### How to install: 
    ng add @progress/kendo-angular-layout

Resources to share out:
- [Color Inspo](https://colorhunt.co/) 
- [Basic TOH Final Repo](https://github.com/alyssamichelle/angular-tour-of-heroes/tree/beginner-ui)
- [TOH Pony Style!](https://github.com/alyssamichelle/kui-tour-of-heroes-releases)
- [Naming Font Size Variables](https://css-tricks.com/the-dilemma-of-naming-font-size-variables)
- [Kendo UI Docs](https://www.telerik.com/kendo-angular-ui-develop/components/layout)

