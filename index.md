### Welcome to my blog

I'm glad you are here. I plan to talk about ...

I am learning how to update the web page.



**Contributors**

{% for stu in site.stu %}
  >> <h2><a href="{{ stu.image }}">{{ stu.user }}</a> @ {{ stu.user }} ({{ stu.name }})</h2>
  <p> >> {{ stu.content | markdownify }}</p>
{% endfor %}
