#HTML.js

## Overview:

A uper simple template fetching toolkit, meant to work with external "partial templates", in
both production and dev enviroments using a templating engine such as underscore


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
