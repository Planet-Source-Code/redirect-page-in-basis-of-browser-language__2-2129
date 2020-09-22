<div align="center">

## Redirect page in basis of browser language


</div>

### Description

If you have a multilanguage web site this simply javascript is for you! You can redirect to a page automatically. The script uses browser/OS language setting and forward to the specified html file.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[NULL](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/empty.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |
**Category**       |[Browser/ System Services](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/browser-system-services__2-69.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/redirect-page-in-basis-of-browser-language__2-2129/archive/master.zip)





### Source Code

```

<!-- ONE STEP TO INSTALL LANGUAGE:
 1. Copy the coding into the HEAD of your HTML document -->
<!-- STEP ONE: Paste this code into the HEAD of your HTML document -->
<HEAD>
<SCRIPT LANGUAGE="JavaScript1.2">
<!-- Begin
if (navigator.appName == 'Netscape')
var language = navigator.language;
else
var language = navigator.browserLanguage;
/*-------------------------------------------------------------
Netscape instructions:
In Netscape, find the language you want to redirect by going to
Edit Menu --> Preferences...
Then click the '+' box next to 'Navigator' and click 'Languages'
Click 'Add' then find the languages you want and add them below.
---------------------------------------------------------------
Microsoft Internet Explorer instructions:
In MSIE, find the language you want to redirect by going to
Tools Menu --> Internet Options...
Then click the 'Languages' button near the bottom of the page.
Click 'Add' then find the languages you want and add them below.
-------------------------------------------------------------*/
if (language.indexOf('en') > -1) document.location.href = 'English.html';
else if (language.indexOf('nl') > -1) document.location.href = 'dutch.html';
else if (language.indexOf('fr') > -1) document.location.href = 'french.html';
else if (language.indexOf('de') > -1) document.location.href = 'german.html';
else if (language.indexOf('ja') > -1) document.location.href = 'japanese.html';
else if (language.indexOf('it') > -1) document.location.href = 'italian.html';
else if (language.indexOf('pt') > -1) document.location.href = 'portuguese.html';
else if (language.indexOf('es') > -1) document.location.href = 'Spanish.html';
else if (language.indexOf('sv') > -1) document.location.href = 'swedish.html';
else if (language.indexOf('zh') > -1) document.location.href = 'chinese.html';
else
document.location.href = 'English.html';
// End -->
</script>
<p><center>
<font face="arial, helvetica" size="-2">Free JavaScripts provided<br>
by <a href="http://javascriptsource.com">The JavaScript Source</a></font>
</center><p>
<!-- Script Size: 1.95 KB -->
```

