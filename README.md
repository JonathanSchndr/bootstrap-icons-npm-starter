# :dolphin: Bootstrap icons npm starter

This template allows you to easily version boostrap icons and your own icons with npm at the same time.

## :rocket: Usage

After cloning the repository you can place your own icons in the icons folder (if you don't have any skip this step). 

Then run `npm install`, your own icons will now be extended with the bootstrap icons. It will create a symlink dist folder where your font will be created. alternatively, you can also run an `npm run icon:generate` later if your own icons have changed.

## :scroll: Documentation

with the command `npm run icon:docs` you call the bootstrap icon docs. also here your custom icons are already included.

## ⚙️ Configuration

the config folder does not need to be changed and is based on bootstrap icon version 1.8.1. if you have specific requirements, you may be able to solve them here. currently, the bootstrap recommendation is stored there.

## :interrobang: Troubleshooting

if you use a new version of the bootstrap icons, you might have to recreate the config folder as well. you can find the current config files in the official bootstrap-icons repo. feel free to create a pull request for it. the version of this package always corresponds to the supported version of the bootstrap-icons.
