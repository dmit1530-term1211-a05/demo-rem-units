# [demo] Relative Rem Units

Relative Units demo using rem. This demo shows how to convert pixels to rem units.

#### Things to know about rem:

- Rem(s) inherit their sizing from the root element (the html element) in which a size is set. 
  -   For example, 16px, 18px or smaller like 10px.
- the 'r' in rem stands for root.
  -   ie. html, :root
-   Unlike ems, rems doesn't have a compounding effect. The child element does not inherit the sizing from its parent but the always from the root size. This makes it incredibly easy to scale all of your sizing on your web pages.
-   As an example: 1rem unit = 16px which is equal to 100%. Assuming that your default browser size is 16px.

## Converting from pixel to rem:

desired size (font, padding, margins, etc.) divided by base/root size (html, :root) = new size in rem units.

For example: Let's say you have a base size of 18px and you want to convert your h1 of 72px to rem units. 
72px = desired size
18px = base size.
new rem size = ?

The math (easy math) = 72px (desired size) / 18px (base size) = 4rem
