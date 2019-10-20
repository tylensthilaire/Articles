---
version: 0.1.0
updated: 2019-10-20
tags: [ , ]
---
<!-- markdownlint-disable MD026 MD033-->

# Picking External Displays For Creatives

Purchase decisions can often present a challenge,
particularly expensive ones
that affect your work.
Your computer monitor probably falls into this category,
if you're in the market for a new monitor concerns typically fall into two categories; how many pixels and how many colours.

***TL;DR:**
Find a screen big enough for your craft and that most accurately matches your intended outputs.*

## How many pixels: Resolution

The resolution you need
largely depends on what you'll be creating
– the rule of thumb being
that you want to see the atrefact you're working on
*and* have room for the UI of your design tool.
For instance,
a 4K movie might need a 5-6K screen,
but only around 2560 px are needed to compare a web design side-by-side with the end product.

## How many pixels: Density

Next you also have the question of Retina/HiDPI displays.
Again, the answer is to consider what you're creating;
if your intended output is a HiDPI display,
design on a HiDPI display,
if not,
don't.

You should also match your screen density to your OS.
macOS and Windows are designed for about 110 ppi and 96 ppi respectively
(220 and 192 for Retina/HiDPI),
straying more than ±10% from these values
will leave the UI looks zoomed in or out<sup><a href="#foot1">[1]</a></sup>.
You could scale the UI,
however doing so creates antialiasing issues
and uses more processing power.
Besides,
just as an 18% grey background keeps your colour perception neutral,
a correctly sized UI keeps your perception of size accurate.

## How many colours? Gamut

Not all screens can display the same colours.
Most screens use the sRGB gamut
but for outputs like phones, movies and photos
a display that supports Display P3, DCI-P3 or Adobe RGB
will match the vibrant colours available in those formats respectively.

Incorrect colour management can produce hyper saturated or flat colours in the final product
which will be invisible on your screen.

## How many colours? Bit Depth

The other thing about a display
is whether it can actually process all the colours you throw at it.
Displays with a lower bit depth will be more susceptible to 'posterisation',
as more colours are shoehorned into a the same number of 'steps' or bits.
Look for 24-bit<sup><a href="#foot2">[2]</a></sup> colour in sRGB displays
and 30-bit<sup><a href="#foot3">[3]</a></sup> colour in wide-gamut displays.

 With more bits,
 you're less likely to see banding and noise
 from posterisation and dithering.

## How many colours? Delta E

Just to complicate things,
the fact that a display can process colours
doesn't necessarily mean it outputs them accurately.
Sometimes, something gets loss in the conversion from digital to physical
(kind of like playing music through an old speaker).
This difference is measured in Delta E (ΔE),
for a screen to accurately display colours,
it should have a ΔE ≤ 2.
At Δ = 2, only a well trained eye could detect the difference in colours,
Δ = 3 is already enough for low contrast colours
(like grey and white)
to appear the same.

## Sidenote: cables and ports

You also need to make sure your comuputer can handle your screen.
Thunderbolt 2 and DisplayPort 1.2 can carry up to 3840×2160 at 60FPS,
which covers screens up to 4K.
More pixels than that and you'll need Thunderbolt 3 or HDMI 2.

<small><ol>
<li title="foot1">Though you could use this to get an easier to read screen for someone who would benefit from a zoomed UI.</li>
<li title="foot2">Marketed as "truetone" or "millions of colours"</li>
<li title="foot3">Marketed as "1.07 billion" or "billions of colours"</li>
</ol></small>

---

## Recap

* Find a screen with enough real-estate to fit both your designs and tools in view.
* Find a screen that supports sRGB, Display P3, Adobe RGB and DCI-P3 for screen, mobile, print and film respectively
* A pixel density of 110 and 96 ppi (220 and 192 for Retina/HiDPI) are the best fit for macOS and Windows respectively, ±10%.
* Look for at least 24-bit colour or 30-bit for wide-gamuts such as Display P3, Adobe RGB and DCI-P3.

### Recommended reading

* [Mac external displays for designers and developers](https://bjango.com/articles/macexternaldisplays/) by Marc Edwards @ Bjango
* [Delta E ≦ 2 Colour Accuracy](https://color.viewsonic.com/explore/content/DeltaE≦2Color-Accuracy_2.html) by Viewsonic

---

*Tylen is an UCD Consultant based in London,
cultivating post-digital ecosystems
for the public and private sectors.
To see or read more about him and his work,
[visit his website](https://tylensthiaire.com/),
or [follow on Medium](https://medium.com/@tylensthilaire_).
To do the same thing but in smaller doses,
head to [Dribbble](https://dribbble.com/tylensthilaire)
or [follow on Twitter](https://twitter.com/tylensthilaire) instead.*
