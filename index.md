---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

##Bootswatch Theme

Bootstwatch theme for Jekyll Bootstrap 3. All Bootswatch themes with a one-line config in your service.

<a href="https://github.com/jekyll-bootstrap-3/bootswatch-theme" class="btn btn-primary">Github</a>

##Install
Inside your jekyll bootstrap 3 directory run:  
{% highlight bash %}
rake theme:install git="https://github.com/jekyll-bootstrap-3/bootswatch-theme"
{% endhighlight %}

##Config
In your `_config.yml`. Add your preferred bootswatch theme:

{% highlight yaml %}
bootswatch-theme: cerulean
{% endhighlight %}
