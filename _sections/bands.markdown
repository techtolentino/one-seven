---
layout: post
title: "Bands"
icon: band-icon.svg
---
A `band` is basically used to visually separate a _section_ of the page. For the most part, bands control the background color of a section. In addition, by using modifiers, you can adjust the top/bottom padding of each band.

<div class="demo">
    <div class="band band--blue-light">blue band</div>
    <div class="band band--red">gray band</div>
    <div class="band band--yellow">yellow band</div>
</div>

{% highlight html %}
<html>
    <body>
        <div class="band band--blue-light">
            blue band
        </div>
        <div class="band band--red">
            gray band
        </div>
        <div class="band band--yellow">
            yellow band
        </div>
    </body>
</html>
{% endhighlight %}
