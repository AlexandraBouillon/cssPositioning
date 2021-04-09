# cssPositioning


- the browser positions a fixed positioned element
  - `position: fixed`
  - always relative to the document, not any particular parent, and are unaffected by scrolling.
  It will always show up at that exact location on the screen, no matter where the user is scrolled to.

- the browser positions a relatively positioned element
  - `position: relative`
  - positioned relative to where it would normally be located; i.e. the element is still in the flow of the document,
  but now left/right/top/bottom/z-index will affect how it is actually displayed.

- the browser positions absolutely positioned elements with and without a relatively positioned parent element
  - `position: absolute`
  - the element is removed from the flow of the document and other elements will behave as if it’s not even there.
  If its positioning is affected by a left/right/top/bottom property, it will use its closest `position: relative` parent as the starting point.
  If no parent is positioned relatively it will use the document in general as its reference.
- the browser positions a static positioned element

  - `position: static`
  - this is the default positioning, so you won't see it written out that often.
  Elements are in their normal page flow, one after the other.
   The positioning properties left/right/top/bottom/z-index do not affect statically positioned elements.
   If we want to use these properties we would need to change the positioning to one of the previously mentioned values.


-sticky positioning`
-original position in the page flow ...
