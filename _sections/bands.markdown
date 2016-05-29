---
layout: section
title: "Bands"
icon: band-icon.svg
---
A `band` is basically used to visually separate a _section_ of the page. For the most part, bands control the background color of a section. In addition, by using modifiers, you can adjust the top/bottom padding of each band.

<div class="demo">
    <div class="demo--section">
        <div class="band demo--block--SPACE">default band</div>
        <div class="band band--secondary demo--block--SPACE">secondary band</div>
        <div class="band band--alt demo--block--SPACE">alt band</div>
    </div>

{% highlight html %}
<html>
    <body>
        <div class="band">
            default band
        </div>
        <div class="band band--secondary">
            secondary band
        </div>
        <div class="band band--alt">
            alt band
        </div>
    </body>
</html>
{% endhighlight %}
</div>
