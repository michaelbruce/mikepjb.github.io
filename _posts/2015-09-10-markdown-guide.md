---
layout: default
title: Markdown tips
tagline: This is what I live for
---

# Markdown tips

- ending lines with two spaces is the equivalent of an html \<br>  

---

- create headers with # for h1, ## for h2 down to ###### h6

---

> Block quotes can be achieved with by starting lines with '> '  

---

* bullets with **\-**, **\*** and **\+**
1. ordered lists with 1. avoid with backticks e.g 1986\\.

---

- Code blocks are made by indenting **twice**:  
Sometimes 3 indents are required (following bullets for example)  

{% highlight ruby %}
def colorize(color_code)
  "\e[#{color_code}m#{self}\e[0m"
end
{% endhighlight %}

Alternatively in jekyll, using highlighting liquid tags you don't need any indentation:  
e.g \{\% highlight ruby \%\} code \{\% endhighlight \%\}

---

Horizontal lines: - - - (3 dashes)

---

Links like so:  
\[text]\(url)  
[an example](http://example.com/ "Title")  

---

\*Italicise\* - *emphasis*  
\**Embolden\** - **emphasis**  
\`backticks\` - `code`

---

!\[A friendly bear]\(friendly_bear.jpg)
![A friendly bear]({{ site.baseurl }}/public/friendly_bear.jpg){: .center-image }

---

Links can be written like so (they are hexed in source code):  
<address@example.com>

---

All markdown syntax can be printed by including backslashes \\{
