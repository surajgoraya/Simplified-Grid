# Simplified-Grid
A lightweight, simple adaptation of Zach Cole's [Simple Grid](https://github.com/zachacole/Simple-Grid)

Originally Developed by Zach Cole, modified by me for use in my personal projects.

## Scripts
This fork of the repo has scripts built in to convert the SCSS to CSS and `min.css` files.

Run: 
```
yarn install && yarn build
```
to get the finalized files in `/bin/`.

## Simple Grid and Simple Code (Original Description)

Simple Grid is a mobile-first 12-column CSS grid system to make developing responsive websites easy and fast.

All the code you need is simple and familiar. A parent container class contains the grid. Within the container are rows. Row classes denote rows of content, which can be filled with up to 12 columns. Columns must be nested within a row. 

To define your column width, declare how many columns you want your content to take up on desktop and large screens. For example, if your content should take up 6 out of 12 columns (or half the container), your class name will be .col-6.

If you don’t want columns to expand on mobile devices and small screens, simply add -sm to the end of your column class name. For example, if you want to have two blocks of content floating side-by-side on small screens, each would be given the class name .col-6-sm.

Learn more and see code samples at: http://simplegrid.io

## License

    Open source under the MIT License.
