# Welcome To My Page !

My name is Farouk. I started this website to be some sort of repository for my technical writings. My main interests are mathematics and programming.

> I would like you to understand that I consider Mathematics more as a question of how rather than a question of what. That is I consider it as the art and science of reasoning as effectively as possible.
>> – Edsger W. Dijkstra

<img src="/Cat-s-Map/photos/0.jpg" style="display: block; margin-left: auto; margin-right: auto; width: 45%; border-radius: 70px;" />

## Articles

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/Cat-s-Map/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
