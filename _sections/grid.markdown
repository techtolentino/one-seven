---
layout: post
title: "Bricks Grid"
icon: grid-icon.svg
---
Ah yes, the `bricks` class! The Brickworks grid uses a flexbox grid system, with the ability to implement _stacking_ at certain breakpoints. The `bricks--layer` is your typical _row_, and every `bricks--item` is equivalent to a column.

<div class="bricks demo">
    <!-- first row -->
    <div class="bricks--layer">
        <div class="bricks--item demo--block">brick 1</div>
        <div class="bricks--item demo--block">brick 2</div>
    </div>
    <!-- second row - stacks on medium breakpoint -->
    <div class="bricks--layer bricks--layer--MEDIUM">
        <div class="bricks--item demo--block--RED">brick 1</div>
        <div class="bricks--item demo--block--RED">brick 2</div>
        <div class="bricks--item demo--block--RED">brick 3</div>
    </div>
    <!-- third row - stacks on small breakpoint -->
    <div class="bricks--layer bricks--layer--SMALL">
        <div class="bricks--item demo--block--YELLOW">brick 1</div>
        <div class="bricks--item demo--block--YELLOW">brick 2</div>
        <div class="bricks--item demo--block--YELLOW">brick 3</div>
        <div class="bricks--item demo--block--YELLOW">brick 4</div>
    </div>
</div>

{% highlight html %}
<div class="bricks">
    <!-- first row -->
    <div class="bricks--layer">
        <div class="bricks--item">brick 1</div>
        <div class="bricks--item">brick 2</div>
    </div>
    <!-- second row - stacks on medium breakpoint -->
    <div class="bricks--layer bricks--layer--MEDIUM">
        <div class="bricks--item">brick 1</div>
        <div class="bricks--item">brick 2</div>
        <div class="bricks--item">brick 3</div>
    </div>
    <!-- third row - stacks on small breakpoint -->
    <div class="bricks--layer bricks--layer--SMALL">
        <div class="bricks--item">brick 1</div>
        <div class="bricks--item">brick 2</div>
        <div class="bricks--item">brick 3</div>
        <div class="bricks--item">brick 4</div>
    </div>
</div>
{% endhighlight %}
