Kennith Ormandy

Precedent: There was a person in history who made a bible with smaller print. 

@font-face
{
    
}

Open Sans is currently the most popular WOFF. 

Subsetting
* normalize-opentext.css
* subsetting unfortunately removes some advanced features of fonts
* subsetting's motivation is to mitigate performance problems

Being Impactful
* woff is from the web fonts working group
* they also created woff2
* Brotli compression allows woff2 files to be smaller than woff files
* 14% to 60% decrease in file size

Fallbacks in the @font-face src
* comma separated.
* this allows the use of woff2
* we can convert woff into woff2 ourselves
* Google Fonts has tools for delivery of fonts and conversion of woff to woff2

Practice
* look for perceived performance improvements
* use typekit/webfontloader to load fonts instead of using css declarations

```
Webfont.load({

    // load these asynchronously

}); 
```
Flash of unstyled text
* this happens when we use async in high latency environments
* the web font loader can include a timeout
* that way, the font style won't change after x seconds... it will change sooner

Summary
* use waff2
* use Webfont.Load (a webkit tool)
* use short timeouts for fallbacks to prevent flash of unstyled fonts
