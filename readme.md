# Danny's Skeleton Theme

A simple child theme for PageLines DMS 1.x and 2.x, containing nothing, but the bare bone (no pun intended) files. The idea behind Skeleton is to provide you to have an insanely basic child theme for which you can build upon.

## Read me!

### I want to name it something else ?

Download Skeleton to your computer and extract the **Skeleton-master.zip**, this will create a folder called **Skeleton-master**. Now simply rename the folder to whatever you like, this is usually your theme name.

### Editing the style.css file

In the **style.css** file, you will find the following:

```
/*
Theme Name: Skeleton
Theme URI: http://www.pagelines.com
Description: Skeleton, a basic child theme for PageLines DMS
Version: 1.0.0
Author: Danny Holt
Author URI: https://github.com/Dannyholt/
Template: dms
*/
```

You can edit all headers except for `Template: dms` which informs Wordpress that this is a DMS child theme.

For example:

```
/*
Theme Name: My Theme Name
Theme URI: http://www.my-website.com
Description: My Themes description goes here...
Version: 6.6.6
Author: My Name goes here
Author URI: http://www.my-website.com
Template: dms
*/
```

### Advanced Users

Although Skeleton is insanely basic, advanced users can get adventurous and include a language, less and sections directories to their theme. Allowing you to add extra functionality and give more control over how your child theme functions.

#### Language Directory

Adding a language folder to your child theme gives you the option to translate your theme into multiple languages.

#### LESS Directory

Copying the **/less** directory that ships with DMS and pasting into your child theme directory, allows you to theme quickly without the need to override the default styling.

#### Sections Directory

One of the cool things about adding a **/sections** directory to your child theme is that, you can override the core sections without having to fear an update wiping your changes.

Want to change how the NavBar functions? Simply copy the **/navbar** directory into your child themes **/sections** directory and edit away.

