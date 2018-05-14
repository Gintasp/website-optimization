# About:

This repo contains completed Final Project of Udacity's course on Website Performance Optimization. This is my first try at optimizing a website for speed. Screenshots of Google Page Speed Insights and Chrome Developer Tools' Performance tests before and after the optimization are available in this repo under the names of "before-optimization.jpg" and "after-optimization.jpg". Sample website is available online at [Github](https://gintasp.github.io/website-optimization/).

=================================================================

# Website Performance Stats:

***BEFORE:***
Render Range 0-975ms,
Page Speed Insights 71(Mobile) & 29(Desktop).

***AFTER:***
Render Range 0-586ms,
Page Speed Insights 99(Mobile) & 97(Desktop).

# Steps I've taken:
1. Optimized Critical Rendering Path.
2. Minified CSS files.
3. Minified JS files and got rid of dead code.
4. Used "async" attribute on one of the blocking scripts.
5. Used "media" atribute for printing, thus unblocked CSS file.
6. Compressed images, converted larger ones to .webp format.
7. Reduced the amount of white space in html files and deleted comments.

# Things I learned doing this project:
1. Gained significant amount of new skills using Chrome Developer Tools.
2. Attained skills for website optimization.
3. Learned about browsers and how they render pages.
4. Deepened my knowledge about DOM, CSSOM and Render Tree.
6. Learned about Critical Rendering Path and best practices to optimize it.
7. Discovered things blocking the rendering process.

