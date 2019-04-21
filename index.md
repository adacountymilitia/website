---
layout: default
title: 1st Battalion, 43rd Field Force, United States Militia
---

We are a volunteer infantry battalion of the Unorganized Militia of the State
of Idaho, based in Ada County. We meet publicly on the first Tuesday of each
month in Meridian, at 7pm, on the upper level of the [Veterans Memorial
Building][map].

We pledge to promote and defend the unalienable rights of all people as
directed by the U.S. Constitution, the Idaho Constitution, and our Commander in
Chief, the Governor of Idaho. If you support this cause, then consider yourself
recruited.

As a Light Foot battalion, we base our operations on the [Militia Standards and
Principles of the Light Foot][standards].

© 2019 Ada County Light Foot

Subscribe: [Atom feed][feed]

{% for post in site.posts %}
<div class="post" markdown="1">
# [{{ post.title }}]({{ post.url }})
<div class="post-metadata">{{ post.date | date: "%Y-%m-%d" }} — by {{ post.author }}</div>
{{ post.content }}

© {{ post.date | date: "%Y" }} Ada County Light Foot
</div>
{% endfor %}

Subscribe to the Ada County Light Foot blog: [Atom feed][feed]


[feed]:      /feed.xml
[map]:       https://www.mapquest.com/search/result?slug=%2Fus%2Fidaho%2Fmeridian%2F83642-2521%2F22-w-broadway-ave-43.610295,-116.393909&query=22%20W%20Broadway%20Ave,%20Meridian,%20ID%2083642-2521&page=0&index=0
[standards]: download/Light_Foot_Militia_Standards_2014.pdf
