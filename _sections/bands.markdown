---
layout: post
title: "Bands"
icon: band-icon.svg
---
A `band` is basically used to visually separate a _section_ of the page. For the most part, bands control the background color of a section. In addition, by using modifiers, you can adjust the top/bottom padding of each band.

<div class="demo">
    <div class="band band--primary-light demo--block--SPACE">primary band</div>
    <div class="band band--danger demo--block--SPACE">danger band</div>
    <div class="band band--warning demo--block--SPACE">warning band</div>
    <div class="band demo--block--SPACE">default band</div>
</div>

{% highlight html %}
<html>
    <body>
        <div class="band band--primary-light">
            blue band
        </div>
        <div class="band band--danger">
            gray band
        </div>
        <div class="band band--warning">
            warning band
        </div>
        <div class="band">
            default band
        </div>
    </body>
</html>
{% endhighlight %}
