## CSS

 - Do not add a space between the property value and the unit (such as `margin-left: 20 px;`). The correct way is: `margin-left: 20px;`
 - An inline style loses many of the advantages of a style sheet (by mixing content with presentation). Use this method sparingly.
 - All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:	
		 - Inline style (inside an HTML element)
		 - External and internal style sheets (in the head section)
		 - Browser default 
- Remember that the `height` and `width` properties do not include padding, borders, or margins! They set the height/width of the area inside the padding, border, and margin of the element!
- When you set the width and height properties of an element with CSS, you just set the width and height of the **content area**. To calculate the full size of an element, you must also add padding, borders and margins.
- Outline differs from borders! Unlike border, the outline is drawn outside the element's border, and may overlap other content. Also, the outline is NOT a part of the element's dimensions; the element's total width and height is not affected by the width of the outline.
- For W3C compliant CSS: If you define the `color` property, you must also define the `background-color`.
- If you do not specify a font size, the default size for normal text, like paragraphs, is 16px (16px=1em). Calculate Pixel with Em = ***`pixels/16= em`***
