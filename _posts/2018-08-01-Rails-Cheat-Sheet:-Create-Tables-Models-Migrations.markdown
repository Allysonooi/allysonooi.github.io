---
layout: post
title:  "Rails Cheat Sheet: Create Tables, Models and Migrations"
date:   2018-08-01 11:56:11
categories: jekyll update
tags: featured
image: /assets/article_images/2016-05-25-welcome-to-jekyll/desktop.jpg
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:
{% highlight ruby %}
$r g model User first_name:string last_name:string description:text mobile_no:integer
$r g migration AddEmailToUser email:string
$r g migration RenameMobileNoToContactNo
$r g migration RemoveDescriptionFromUser email
{% endhighlight %}


Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

{% highlight js %}

<footer class="site-footer">
<div class="inner">a
  <section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; {{ site.time | date: '%Y' }} &bull; All rights reserved.</section>
  <section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
 </div>
</footer>
{% endhighlight %}


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
