---
views:
    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
---
Rubrik 1
=========

Här kan man ju skriva nåt kul, eller tråkigt.

Rubrik 2 - Språk
------------
* Hej
+ Guten Tag
- Hello

1. Svenska
2. Tyska
3. Engelska

### Rubrik 3

<div class="testdiv">
  [FIGURE src="image/fontana.jpg?h=200&crop-to-fit" srcet="fontana@2x.jpg 2x" alt="Fontana di Trevi"]
</div>
<div class="testdiv test01">
  [FIGURE src="image/tree2.JPG?h=200&area=0,10,0,10"  alt="träd" srcet="tree2@2x.JPG 2x"]
</div>
<div class="testdiv">
  [FIGURE src="image/borga.JPG?w=200" srcet="borga@2x.JPG 2x" alt="Borgafjäll"]
</div>

<br>

<div class="line"></div>

<div class="testdiv2">
  <div class="test2">
    [FIGURE src="image/tree2.JPG?h=150&&area=0,10,0,10" alt="träd" srcet="tree2@2x.JPG 2x"]
  </div>
</div>

<div class="testdiv2">
  <div class="test2">
    [FIGURE src="image/tree2.JPG?h=150&&area=0,10,0,10" alt="träd" srcet="tree2@2x.JPG 2x"]
  </div>
</div>
