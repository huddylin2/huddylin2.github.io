---
layout: post
title: A little bit about Huddy
subtitle: And also why I think Marshawn is the GOAT
tags: [Football, Skittles, Hennesy]
comments: true
mathjax: true
author: Hudson Lin
---

{: .box-success}
Read this blog post to learn more about my **name, year, major, sewing, programming, learning hops, and boring fact about me**

## Lets Go

Hi my name is **Hudson or Huddy** and I am a junior in the class of **2027**. I am a **political science major**. I have **very limited** sewing experience so I am basically starting as a beginner. I have taken coding classes in the past but I always struggled a lot understanding coding so I would say that my coding experience is **very limited** if any. A learning hope that I have is to learn some **basic tech skills** because I think that understanding technology will be the future of industry. A boring fact about me that is actually not that boring is that **I LOVE MARSHAWN LYNCH**. That's why he's my profile page icon. On the field he is one of the most dominant running backs in NFL history in my humble opinion. You can watch some of his highlights [here](https://www.youtube.com/watch?v=kXOZdMeSIEo). There is a reason Marshawn is called _beast mode_. Off the court he is one of the funniest guys to do it. watch his funnies moments [here](https://www.youtube.com/watch?v=rzY-NUxiSpI). One last point on my soapbox. Following his retirement from the NFL, he can be seen taking pictures on the field. 

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})

<details markdown="1">
<summary>Click here!</summary>
Here you can see an **expandable** section
</details>
