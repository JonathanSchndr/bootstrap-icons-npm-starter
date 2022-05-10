# bootstrap icons npm starter

with this repo you can easily version boostrap icons via npm and add your own icons at the same time.

## use

if you don't have your own icons, you just need to run an `npm install`. if you have your own icons that you want to extend the bootstrap icons with, put them in the icons folder first. then run an `npm install`. it will create a symlink dist folder where your font will be created. alternatively, you can also run an `npm run icon:generate` later if your own icons have changed.

## docs

with the command `npm run icon:docs` you call the bootstrap icon docs. also here your custom icons are already included.

## config

the config folder does not need to be changed and is based on bootstrap icon version 1.8.1. if you have specific requirements, you may be able to solve them here. currently, the bootstrap recommendation is stored there.

## trouble

if you use a new version of the bootstrap icons, you might have to recreate the config folder as well. you can find the current config files in the official bootstrap-icons repo. feel free to create a pull request for it. the version of this package always corresponds to the supported version of the bootstrap-icons.
