Shay Howe

github.com/bellycard/rolodex

Home Page <---- Toolkit ----> Style Guide

The Toolkit Implementation

Single responsibility principle
* every class should have a single responsibility 
* e.g. .alert, .alert-error
* put each into its own module

Decouple HTML and CSS
* remove parent container dependency
* allows elements to adapt
* e.g. feat-box, .feat-box-alt

Name with Care
* name for understanding
* favour functional names
* use a sensible pattern

Avoid unecessary specificity
* `.button` is better than `form .button`
* unless of course we have reason to nest

Use predictable patterns
 
Use Maps
* this is a SAAS technology

Use Mixins
* these let us share a common group of styles
* only groups of styles not a single declaration
* for single declarations, use a variable instead
* use the single responsibility rule

Measure your Improvements
* identify a baseline
* select a few KPIs (File size, number of rules, number of selectors...)
* Look into StyleStats, CSSCSS, CSS Lint & Web Page Stat

Don't Over Think
* Write out code the long way, then refactor
* Rename, rewrite, refactor willingly
* Document everything
