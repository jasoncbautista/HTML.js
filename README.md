#HTML.js

## Overview:

A super simple template fetching toolkit, meant to work with partials"/templates, in both production and dev environments using a templeting engine such as underscore.

# Deps:

jQuery
underscore

# Soft Depencencies:

You can use underscore by default or hook up your own templating system.

# Usage:

```
    var template_str = HTML.getTemplateString("someTemplateName");
    var reusableTemplate = _.template(template_str);
    // Do something with the reusable template
    $(".some-holder").append( reusableTemplate({"name": "UserX", "title": "Super User"}));


    // Or just get an underscore tempalte directly
    var reusebleTemplateTwo = HTML.getTemplate("someTemplate");


```

### TODO:
Open source compiler program for template files.
[ ] example folder with an index.html and a few exampe templates

[ ] html_compiler.py 
[ ]  just take params , or env variables

[ ] reads files in single directory , eventually we might want recurive
[ ] include a lazy loading directory too...
so
/tempaltes/partials
/tempaltes/lazyLoadPartials


index.html
-----------------------
...

<div class="html-include-templates-lazy-load">
<!-- priamry set of templates-->
</div>






