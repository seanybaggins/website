+++
author = "Sean Link"
title = "Inverted Pendulum"
date = "2021-01-06"
description = "Gains derivation for the inverted pendulum"
tags = [
    "Inverted Pendulum", "Controls", "Linear Algebra",
]
+++

One of the coolest things I did during my education was implement a controller
for an inverted pendulum. See the following video.

{{<youtube w2OGMYozBlk>}}

There was only one problem. While I implementd the controller to control
the inverted pendulum, I did not derive the model. That was given to me by my
instructor. Even though implementing the controller was cool, it was somewhat
unsatisfying. After all, I really had no idea how the model was derived. It was a
black box that I took for granted to be true and correct. In order to better
understand this black box, I decided to sit down and derive the model of the
inverted pendulum myself. And oh man, I now understand why my instructor decided
to just give it to me. Below is my derivation for the model of the inverted
pendulum. I tried to make the derivation as approachable as possible and link to
other resouces when I felt appropriate. Enjoy.

{{< rawhtml >}}
<iframe src=/website/gains-derivation.html
        height=13269.0px
        width=100%
        style="border:none;overflow:hidden;"
        scrolling="no">
</iframe>
{{< /rawhtml >}}

