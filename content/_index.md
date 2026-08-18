+++
title = "Neil Makur"
sort_by = "weight"
template = "index.html"
+++

<div class="parallel-img">
<div class="text-wrapper">

Welcome! My name is Neil Makur, and I'm a student studying <color val="green">Computer Science</color> and <color val="green"> Mathematics</color> at <color val="red">Carnegie Mellon University</color>, graduating in 2028.

I have a bunch of interests, here are my top ones:
- <color val="magenta">Commitment to the bit</color>: always my first priority
- <color val="magenta">Mathematics</color>: particularly algebra and number theory, with a bit of geometry/topology
- <color val="magenta">Computer Systems and Hardware</color>: how in the world we managed to use inanimate objects to watch cat videos on demand
- <color val="magenta">Computer Performance</color>: compilers, optimizing code to run on specific hardware, and understanding the software/hardware interface in general
- <color val="magenta">Event Production</color>: handling technical and logistical needs for concerts, carnivals, conventions, and also probably things that don't start with c.

</div>
<div class="image-wrapper">
{% set me_on_subs = resize_image(path="images/subs.png", width=400, height=400, op="fit") %}
<img src="{{ me_on_subs.url }}" width="{{ me_on_subs.width }}" height="{{ me_on_subs.height }}"
  style="border: 1px solid var(--cyan-color);"/>
</div>
</div>

Since you're here, you might be interested in the following:
- [Mathy things I've written](/library)
- [Assorted fun facts](/fun_facts)
- My thoughts about [CMU](/cmu) or [my summers](/summers)
- [More about me](/about)

Not sure what you'd like? Take a look at the [root directory](/root).
