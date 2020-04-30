### Welcome to my blog

I'm glad you are here. I plan to talk about ...

I am learning how to update the web page.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

