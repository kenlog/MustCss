# MustCss
Theme for Kanboard - Kanban project management software

CSS plugin
------------
This plugin add a new stylesheet and override default styles.

Requirements
------------
Kanboard >= v1.2.5  
Kanboard installed at a web server.
You can find the download at [kanboard.org](https://kanboard.org/)

Installation
------------
Open the terminal in the plugins folder. Note that you don't need to create a new directory for MustCss, as cloning the repository via git will create a directory for you. 

Now, clone the repository: ```git clone https://github.com/kenlog/MustCss.git```

**otherwise**
- Create a directory **MustCss** under the folder **plugins**
- Copy all source files into this new directory

Add options for the theme
------------
- Replace the KB logo with your own logo  
For more information have a look in the config.php

Syntax highlight code by Prism
------------
151 languages currently supported by Prism, with their corresponding alias, to use in place of php
- example:  
```diff
-```
+```php
class BaseClass {
    function __construct() {
        print "In BaseClass constructor\n";
    }
}
+```
```

Author
------------
- Valentino Pesce
- License MIT

Reporting Issues
------------
Please [create an issue](https://github.com/kenlog/MustCss/issues) for any bugs you've found.

# Screenshot
![screen-board-3](https://user-images.githubusercontent.com/11728231/42727267-b8754144-87a3-11e8-8c3d-6151fa92b76d.jpg)
![screen-task-2](https://user-images.githubusercontent.com/11728231/42726115-91f9972c-878f-11e8-83b6-ef533f34327e.jpg)
![screen-task-1](https://user-images.githubusercontent.com/11728231/42726116-922fd0bc-878f-11e8-99da-76aecf8fd97d.jpg)
![screen-highlight](https://user-images.githubusercontent.com/11728231/42735774-4bcaa50e-885a-11e8-8018-0649620ce795.jpg)
