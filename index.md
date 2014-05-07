---
layout: page
---
{% include JB/setup %}

大阪を拠点にWebアプリ・Webサービス・モバイル（iOS/Android）アプリの開発を行っております。

アプリやサイトを作りたいのに人手が足りない、そのような場合はぜひ一度[お問い合わせ](/contact.html)ください。

## お知らせ

<ul class="posts">
  {% for post in site.categories.press %}
    <li><span>{{ post.date | date: "%F" }}</span> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
