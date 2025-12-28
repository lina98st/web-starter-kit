# web-starter-kit

A simple, long term starter kit for classic websites  
HTML, CSS and optional vanilla JavaScript  
No frameworks, no build tools, no overengineering

## Purpose

This repository is a reusable base for building websites  
It provides a clean structure, basic layout and neutral default styles  
The focus is clarity, simplicity and easy customization

## Project Structure

### /
- index.html
- README.md

### /pages
- about.html
- career.html
- location.html
- contact.html

### /css
- main.css

#### /css/base
- reset.css
- variables.css

#### /css/layout
- layout.css
- nav.css

#### /css/components
- header.css
- footer.css

### /js
- main.js

### /assets
- images
- fonts



## HTML

- `index.html` is in the root for maximum hosting compatibility
- Each additional page lives in the `pages` folder
- One HTML file per page, no templating

## CSS

All styling lives in the `css` folder.

### main.css

- Entry point for all styles
- The only CSS file linked in HTML
- Imports all other CSS files

### base

Global foundation styles used by the entire site

- `reset.css` browser default reset
- `variables.css` colors, fonts, spacing and design tokens

### layout

Defines the page structure

- Overall layout using Flexbox
- Header, navigation, main content and footer positioning
- Right side navigation styles

### components

Styles for individual, reusable UI parts

- Header styles
- Footer styles
- Buttons and other small components

## JavaScript

- Optional
- Only used when needed
- Keeps behavior separate from structure and style

## Assets

Static files used by the site

- Images
- Fonts
- Icons

## Philosophy

Keep it simple  
Write semantic HTML first  
Add CSS for layout and design  
Use JavaScript only when necessary
