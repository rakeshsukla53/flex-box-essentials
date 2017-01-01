# flex-box-essentials

# Links

- https://www.w3.org/TR/css-flexbox-1/

# flex-foreshadowing

- Flex items are direct children of a flex container and can be HTML elements or text
- Grandchild elements do not become flex items

# Wily Wrapping

- This property's default value is nowrap and it accepts: nowrap | wrap | wrap-reverse
- flex-direction default value is row
- when you wrap, you also define the `align rows` properties


# flex-overriding

- you can override the flex layout of an individual element inside of a flex container
selecting it and applying Flex Child Settings

 
# Sizing Presets

- You can change the sizing presets of the flex children. Look for flex child elements properties
- You can combine the sizing presets with width or height as well
- If you need a flex child to span across the full width of its parent container, then just its width to 100% or 50%
if you want to occupy only half
- sizing, align and order are three properties of the flex child elements
- flex child elements will override the flex container property but other properties of flex-container will be applied
to the child elements
 
# Order of the Child Elements

- Order of the child elements can also be changed using flex child settings


# flex-grow
 
- The flex-grow CSS property specifies the flex grow factor of a flex item. It specifies what amount of space inside the flex container the item should take up.
https://developer.mozilla.org/en-US/docs/Web/CSS/flex-grow

# order 

- The CSS order property specifies the order used to lay out flex items in their flex container. 
Elements are laid out in the ascending order of the order value. Elements with the same order value are laid out 
in the order in which they appear in the source code.

- https://developer.mozilla.org/en-US/docs/Web/CSS/order

    The order property applies to flex items only.
    We can use the order property to change the order of any flex item.
    You can structure an HTML document for SEO or accessibility first, then rearrange the content without ever editing the HTML.
    The default order of all flex items is 0.
    order places flex items relative to the other items' order values.
    To place a flex item before another item, it needs to have a lower order value than the item.
    To place a flex item after another item, it needs to have a higher order value than the item.


# flex-wrap

    The flex-wrap property is for flex containers only.
    The flex container lays out flex items on a single line called a flex line.
    The flex container tries to fit all items on one flex line, even if causes its contents to overflow.
    The flex container can break flex items into multiple flex lines and allow them to wrap as needed.
    With the flex-wrap property, you can control whether the flex container is a single-line or multi-line layout.
    The value wrap breaks the flex items into multiple lines.

# space around for flex items


    You apply the justify-content property to flex containers only.
    The justify-content property lets you control the position and alignment of flex Items on the main axis and how space should be distributed in a flex container.
    The default value for justify-content is flex-start, which places items towards the start of each flex line.
    To place items at the end of the flex line, set justify-content to flex-end.
    The value center places flex items in the center of the line, with equal amounts of empty space between the line's start edge and the first item.
    The value space-between displays equal spacing between flex items.
    For equal spacing around every flex item, use the value space-around.
    A margin set to auto will absorb any extra space around a flex item and push other flex items into different positions.

# flex-grow property is everything you need 

    The flex-grow property applies to flex items only.
    flex-grow determines how much of the available space inside the flex container an item should take up; it assigns more or less space to flex items.
    A flex-grow value of 1 expands flex items to take up the full space of a line.
    The higher the flex-grow value, the more an item grows relative to the other items.

