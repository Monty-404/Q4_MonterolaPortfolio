Step 1: 
Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
Answer: While going farther, it is mostly positioned relative to its normal position.

Step 2:
Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?
Answer: When you try scrolling, it just remains in a specific place. It

Step 3:
Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?
Answer: Absoulute positioning allows an element to be positioned relative to its neareat positioned ancestor. On the other hand, Fixed is positioned relative to the viewport. The scrolling shows the absolute going along with the page, while fixed remains presents and seen throughout.


Step 4:
Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?
Answer: The z-index indiciates the order of the vertical stacking of elements. The z-index allows the notice to appear on top of the content. Swapping the z-index shows that the element with the greater z-index goes behind the element with the less z-index.


Reflection
a. Could you summarize the differences between the CSS position values (static, relative, absolute, fixed)?

Static allows the the default positoning, but relative, as the name suggests, makes the element positioned relative to the static. Absolute is still positioned relative but instead to it's nearest positioned ancestor. On the other hand. Fixed positions itself relative to the viewport.


b. How does absolute positioning depend on its parent element?
It follows according to the nearest ancestor with the ancestor's position value.

c. How do you differentiate sticky from fixed (you can research on sticky)?

Fixed is constant, while sticky almost acts like position: absolute.
After threshold, sticky becomes fixed.


d. If you were designing a webpage for a school event, how might you use positioning to highlight important information? Please give concrete examples

For contact details regarding the school event, the fixed position would be used on the footers and heads. For the main information, they would have a low z-index to easily be seen.