---
layout: section
title: "Layers"
icon: layer-icon.svg
---
A `layer` is basically used to visually separate a _section_ of the page. For the most part, layers control the background color of a section. In addition, by using modifiers, you can adjust the top/bottom padding of each layer.

<div class="demo">
    <div class="demo--section">
        <div class="layer demo--block--SPACE">default layer</div>
        <div class="layer layer--secondary demo--block--SPACE">secondary layer</div>
        <div class="layer layer--alt demo--block--SPACE">alt layer</div>
    </div>

{% highlight html %}
<html>
    <body>
        <div class="layer">
            default layer
        </div>
        <div class="layer layer--secondary">
            secondary layer
        </div>
        <div class="layer layer--alt">
            alt layer
        </div>
    </body>
</html>
{% endhighlight %}
</div>
