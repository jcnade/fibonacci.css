# fibonacci.css
Tiny Fibonacci CSS Framework By Jean-Charles Nadé


When we design a layout, we pick up arbitrary a number who looks nice in base 10. For a column, we will select probably a width of 350 pixels with 10 pixel as padding-top, right? 

What happen if we use Fibonacci number for our layout? Maybe 377 pixel and 13px as padding-top will looks better.

This little framework provide shortcut for Fibonacci number for padding, margin, with and height.


CSS Class Exemple: 

* w10 = a width of 55px
* w11 = a width of 144px
* w12 = a width of 233px
* pl6 = a padding left at 13px

Usage exemple:keyword+Number:

    <div class="w12 h11 p5 ml4" >
        This boxBox is 233px width, 144px height, 13px for padding and 5px as margin-left.
    </div>

Shortcut:

* w = width 
* h = height
* p = padding
* m = margin
* pl = padding-left
* pr = padding-right
* pb = padding-bottom
* pt = padding-top
* ml = margin-left
* mr = margin-right
* mb = margin-bottom
* mt = margin-top
