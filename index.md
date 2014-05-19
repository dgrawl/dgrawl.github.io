
---
title: 新闻列表
layout: newslist1

---


<div class="label_content">
    <div class="item_list id383">
      <ul class="clearfix" id="hrieList407" style="min-height: 140px;">
        {% for post in paginator.posts %}
          {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
          <li class="animated wobble">
            <a title="{{ post.title }}" href="{{ post.url }}">{{ post.title }}</a>
      
            
          </li>
        {% endfor %}
        </ul>
      
    </div>
  </div>