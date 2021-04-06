# CSS Flexbox

## CSS Flex Container (Parent Element)

The flex container properties are:
<ul>
<li>flex-direction</li>
<li>flex-wrap</li>
<li>flex-flow</li>
<li>justify-content</li>
<li>align-items</li>
<li>align-content</li>
</ul>

The flex-direction property defines in which direction the container wants to stack the flex items.
<ul>
<li>The __column__ value stacks the flex items vertically (from top to bottom).</li>
<li>The __column-reverse__ value stacks the flex items vertically (but from bottom to top).</li>
<li>The __row__ value stacks the flex items horizontally (from left to right).</li>
<li>The __row-reverse__ value stacks the flex items horizontally (but from right to left).</li>
</ul>

The flex-wrap property specifies whether the flex items should wrap or not.
<ul>
<li>The __wrap__ value specifies that the flex items will wrap if necessary.</li>
<li>The nowrap value specifies that the flex items will not wrap (this is default).</li>
<li>The wrap-reverse value specifies that the flexible items will wrap if necessary, in reverse order.</li>
</ul>

The __flex-flow__ property is a shorthand property for setting both the __flex-direction__ and __flex-wrap__ properties.

The justify-content property is used to align the flex items.
<ul>
<li>The center value aligns the flex items at the center of the container.</li>
<li>The flex-start value aligns the flex items at the beginning of the container (this is default).</li>
<li>The flex-end value aligns the flex items at the end of the container.</li>
<li>The space-around value displays the flex items with space before, between, and after the lines.</li>
<li>The space-between value displays the flex items with space between the lines.</li>
</ul>

The align-items property is used to align the flex items.
<ul>
<li>The center value aligns the flex items in the middle of the container.</li>
<li>The flex-start value aligns the flex items at the top of the container.</li>
<li>The flex-end value aligns the flex items at the bottom of the container.</li>
<li>The stretch value stretches the flex items to fill the container (this is default).</li>
<li>The baseline value aligns the flex items such as their baselines aligns.</li>
</ul>

The align-content property is used to align the flex lines.
<ul>
<li>The space-between value displays the flex lines with equal space between them.</li>
<li>The space-around value displays the flex lines with space before, between, and after them.</li>
<li>The stretch value stretches the flex lines to take up the remaining space (this is default).</li>
<li>The center value displays display the flex lines in the middle of the container.</li>
<li>The flex-start value displays the flex lines at the start of the container.</li>
<li>The flex-end value displays the flex lines at the end of the container.</li>
</ul>

## CSS Flex Items (Child Elements)

The flex item properties are:
<ul>
<li>The <u>order</u> property specifies the order of the flex items.</li>
<li>The <u>flex-grow</u> property specifies how much a flex item will grow relative to the rest of the flex items.</li>
<li>The <u>flex-shrink</u> property specifies how much a flex item will shrink relative to the rest of the flex items.</li>
<li>The <u>flex-basis</u> property specifies the initial length of a flex item.</li>
<li>The <u>align-self</u> property specifies the alignment for the selected item inside the flexible container.</li>
</ul>









