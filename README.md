# Feed Me Branding

A repository for Feed Me, Jefferson brand assets and style guidelines.

## Under Contruction

This repo is going quickly converging on what will hopefully eventually be a meaningful structure. For now see the [doc](doc) folder for any resources that are purely documentational including brand guidelines and style tiles. 

The [src](src) folder should contain all of the source files necessary for building the theme specific assets that get deployed with Feed Me, Jefferson. Think of this as a prebuild step for resources that get copied over to the theme folder in the preact based project (and only need to get rebuilt when the mostly static assets change).

## Building the Themes

Right now there are a few npm scripts in the `package.json` file, but they are potentially out of date. They worked well enough for getting started when we were only building one theme, but now that we've separated out each of the themes into it's own folder, we might need to push the logic into an `index.js` file (we might even use something like webpack). 

## Theme vs Model

In this case, I'm using model in the _**machine learning**_ way rather than in the _**Model/View/Controller**_ type of way. 

Currently our application's build process is combining the food space model and the theme. Ideally each of these would be completely independently pluggable rather than bound together. If we ever get there, then maybe this repo will be 100% responsible for building the theme folder and another repo can be responsible for building a similar model folder. 