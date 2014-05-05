---
layout: page
title: Help
---

Skeleton was developed by PageLines [Danny Holt](https://github.com/Dannyholt/) to give DMS users an effective foundation for building DMS themes. Due to Skeletons simplicity, it allows for quick and efficient theming.

### Two Versions ?

Skeleton contains two branches or versions, these are Basic and Advanced.

#### Basic

The Basic version (branch) consists of only the essential files required for a DMS child. These files are **functions.php**, **style.css** and **style.less**.

{% highlight %}
skeleton/
├── functions.php/
├── style.css/
├── style.less/
{% endhighlight %}

#### Advanced

The Advanced version (branch) consists the essential files as well as a **less** directory and **sections** directory. These allow you to go override the default styling of DMS and create childs of the core sections bundled with DMS.

{% highlight %}
skeleton/
├── less/
│   ├── variables.less/
├── sections/
│   ├── dannys-masthead/
├── functions.php/
├── style.css/
└── style.less/
{% endhighlight %}
