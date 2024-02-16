z-index

The z-index property in CSS controls the vertical stacking order of elements that overlap. As in, which one appears as if it is physically closer to you. z-index only affects elements that have a position value other than static (the default).

Elements can overlap for a variety of reasons, for instance, relative positioning has nudged it over something else. Negative margin has pulled the element over another. Absolutely positioned elements overlap each other. All sorts of reasons.

Without any z-index value, elements stack in the order that they appear in the DOM (the lowest one down at the same hierarchy level appears on top). Elements with non-static positioning will always appear on top of elements with default static positioning.

Also note that nesting plays a big role. If an element B sits on top of element A, a child element of element A can never be higher than element B.