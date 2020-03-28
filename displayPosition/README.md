# Box Model

- The box model comprises a set of properties used to create space around and between HTML elements.
- The height and width of a content area can be set in pixels or percentage.
- Borders surround the content area and padding of an element. The color, style, and thickness of a border can be set with CSS properties.
- Padding is the space between the content area and the border. It can be set in pixels or percent.
- Margin is the amount of spacing outside of an element’s border.
- Horizontal margins add, so the total space between the borders of adjacent elements is equal to the sum of the right margin of one element and the left margin of the adjacent element.
- Vertical margins collapse, so the space between vertically adjacent elements is equal to the larger margin.
- margin: 0 auto horizontally centers an element inside of its parent content area, if it has a width.
- The overflow property can be set to display, hide, or scroll, and dictates how HTML will render content that overflows its parent’s content area.
- The visibility property can hide or show elements.



Box model is composed of the following:
- height
- width
- padding
- border
- margin
- overflow


# Box Model: Border-Box

`* {
  box-sizing: border-box;
}`
![alt text](border-box.jpg)
