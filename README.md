## Name:
chxw

## Date:
6/2/2020

## Summary:
A personal portfolio created from scratch using HTML5/CSS. The three required personal web pages:

`resume.html` - Your resume. Real or fictitious. 
1. Full name or handle
2. Education
3. Relevant Coursework
4. Professional Experience.
5. Skills.
6. Activities that are related to your field of study or work.

`bio.html` - A short biography of yourself. Real or fictitious. 

`index.html` - Personal home page. 
1. Your name.
2. Photo of you.
3. Link to resume
4. Link to short biography.

## Files:
```
.
├── README.md
├── bio.html
├── font
│   ├── LICENSE.txt
│   ├── OFL.txt
│   ├── Roboto-Black.ttf
│   ├── Roboto-BlackItalic.ttf
│   ├── Roboto-Bold.ttf
│   ├── Roboto-BoldItalic.ttf
│   ├── Roboto-Italic.ttf
│   ├── Roboto-Light.ttf
│   ├── Roboto-LightItalic.ttf
│   ├── Roboto-Medium.ttf
│   ├── Roboto-MediumItalic.ttf
│   ├── Roboto-Regular.ttf
│   ├── Roboto-Thin.ttf
│   ├── Roboto-ThinItalic.ttf
│   ├── Rubik-Black.ttf
│   ├── Rubik-BlackItalic.ttf
│   ├── Rubik-Bold.ttf
│   ├── Rubik-BoldItalic.ttf
│   ├── Rubik-Italic.ttf
│   ├── Rubik-Light.ttf
│   ├── Rubik-LightItalic.ttf
│   ├── Rubik-Medium.ttf
│   ├── Rubik-MediumItalic.ttf
│   ├── Rubik-Regular.ttf
│   ├── roboto-regular-webfont.woff
│   ├── rubik-regular-webfont.woff
│   └── themify.svg
├── images
│   └── me.jpg
├── index.html
├── resume.html
├── stylesheet.css
└── svg
    ├── flickr.svg
    ├── github.svg
    ├── home.svg
    ├── link.svg
    ├── stack-overflow.svg
    └── vimeo-alt.svg
```

## Reflection:

The requirements and guidelines of this assignment were completed/followed. The website looks what I intended it to look like. I used a "grid system" in my stylesheet. Some things to improve on in this implementation is
1. Everything related to padding, margin, gutters, gaps, etc. 
2. Next time it would be good to create a "design system". Something to better organize and keep track of cascading hierarchies. I'm sure there are redundancies / inefficiences in my stylesheet -- there was a lot of trial-and-error work instead of systematized work. 
3. Making sure the website is supported by all browsers. For example, for the `@font-face` rule, the following could be added to ensure fonts are supported by various browsers:

```
/*@font-face {
    font-family: 'Inlove';
    src: url('inlove-light-wf.eot'); /* IE9 Compat Modes */
    src: url('inlove-light-wf.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
         url('inlove-light-wf.woff') format('woff'), /* Modern Browsers */
         url('inlove-light-wf.ttf')  format('truetype'), /* Safari, Android, iOS */
         url('inlove-light-wf.svg#svgFontName') format('svg'); /* Legacy iOS */
}*/ 
```

Respect to whoever is really good at CSS. I spent \~7 hours on this, and the page still feels pretty ugly. Maybe I'll try a 'minimalist' look next pass. 

## References:
SVG icons are from themify (their CSS stylesheet was NOT used in this). Retrieved from [https://themify.me/themify-icons](https://themify.me/themify-icons).

[https://www.sitepoint.com/a-basic-html5-template/](https://www.sitepoint.com/a-basic-html5-template/).

[https://www.developerdrive.com/how-to-create-a-css-grid-step-by-step/](https://www.developerdrive.com/how-to-create-a-css-grid-step-by-step/).

[https://www.w3schools.com/howto/howto_css_icon_bar.asp](https://www.w3schools.com/howto/howto_css_icon_bar.asp).

[https://stackoverflow.com/questions/7025756/how-to-apply-global-font-to-whole-html-document](https://stackoverflow.com/questions/7025756/how-to-apply-global-font-to-whole-html-document).

[https://stackoverflow.com/questions/8919682/remove-all-styling-formatting-from-hyperlinks/8919740](https://stackoverflow.com/questions/8919682/remove-all-styling-formatting-from-hyperlinks/8919740).

[https://stackoverflow.com/questions/12589758/font-face-doesnt-work#:~:text=One%20source%20of%20the%20problem,not%20to%20the%20root%20folder.](https://stackoverflow.com/questions/12589758/font-face-doesnt-work#:~:text=One%20source%20of%20the%20problem,not%20to%20the%20root%20folder.)
