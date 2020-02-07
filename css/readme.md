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
- ***CSS Position***
	- Static : Not required to use, it normal document flow.
	- Relative : Same as Static, but it can change all over the document such as (Left, Right, Top, Bottom)
	- Absolute : Out from normal document flow and change all over document by (Top, Left, Right, Bottom).
	- Fixed : Fixed the div if other content or what ever else.  

- ***CSS Overflow***
	- The `overflow` property specifies whether to clip the content or to add scrollbars when the content of an element is too big to fit in the specified area.
	- The `overflow` property only works for block elements with a specified height.
	- **Overflow : Visible :** Show content outside div, but not clipped.
	- **Overflow : Hidden:** Don't show content outside of div, clipped the content.
	- **Overflow : Scroll:** Add scroll in vertical and horizontally, if content occupied, also show scrollbar.
	-  **Overflow : Auto:** The `auto` value is similar to `scroll`, but it adds scrollbars only when necessary.
	- **overflow-x:  hidden :** Hide horizontal scrollbar.
	- **overflow-y:  scroll:** Add vertical scrollbar
- **What is box-sizing?** 
	- You can easily create three floating boxes side by side. However, when you add something that enlarges the width of each box (e.g. padding or borders), the box will break. The `box-sizing` property allows us to include the padding and border in the box's total width (and height), making sure that the padding stays inside of the box and that it does not break.

- Compared to `display: inline`, the major difference is that `display: inline-block` allows to set a width and height on the element.
- Compared to `display: block`, the major difference is that `display: inline-block` does not add a line-break after the element, so the element can sit next to other elements.
- **Alignment :**
	- To horizontally center a block element (like div), use `margin: auto;`
	- To center an image, set left and right margin to `auto` and make it into a `block` element: