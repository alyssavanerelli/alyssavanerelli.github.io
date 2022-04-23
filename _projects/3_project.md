---
layout: page
title: boa mitogenomes
description: Assembling mitochondrial genomes for an entire genus of Caribbean boas
img: assets/img/argentum_pic.jpeg
importance: 3
category: past research
---

This is the research that I completed for my <i class="fas fa-file"></i> <a class="link" href="{{ '/assets/pdf/thesis_paper.pdf' | prepend: site.baseurl | prepend: site.url 
}}">undergraduate thesis</a> at UNC Asheville in the [Reynolds Lab](https://reynoldslab.wp.unca.edu/). 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/argentum_pic.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A Conception Bank Silver Boa (<em>Chilabothrus argentum</em>), the world’s most endangered boa. This adult female is one of only 135 adult animals remaining in the entire species. Photograph by 
R. Graham Reynolds. 
</div>

_Chilabothrus_ is a completely insular genus of boid snakes occurring throughout the West Indies. The genus is composed of 14 species and nearly half of these species are newly described or recently
elevated species<d-footnote>Reynolds RG, Niemiller ML, Hedges SB, Dornburg A, Puente-Rolón AR, Revell LJ. 2013. Molecular phylogeny and historical biogeography of West Indian boid snakes. Mol. 
68:461-470.</d-footnote>. Several species within this genus face serious conservation concerns such as introduced predators, anthropogenic habitat destruction, poaching for the pet trade, and low 
genetic diversity<d-footnote>Reynolds RG, Puente-Rolón AR, Geneva AJ, Aviles-Rodriguez KJ, Herrmann NC. 2016. Discovery of a
remarkable new boa from the Conception Island Bank, Bahamas. Breviora. 549:1-19.</d-footnote>.




<d-footnote>This will become a hoverable footnote.</d-footnote>















<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
