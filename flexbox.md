### Somes Rules on Flexbox

[1]

Use the parent to modify the position of the childern elements, to position the childern they must be inside of a flex container

[2]

By default the flex direction of a flex container is `Row`, `rows` are horiztonal and `columns` are vertical.
For flex direction `Row` the main axis is horizontal while the vertical axis is the cross axis
> to modify or move items on the main axis we use the `justify-content` property and for cross axis we use the `align-items` property.

[3]
Flex direction `coulmn` the main axis is vertical while the cross axis is horizontal, `justify-content` porperty will move items on the main axis which is now vertical since our flex direction is `column`, and `align-items` property will also move items on the cross axis.

### Note:

1. `justify-content` moves items on the main axis while `align-items` moves items on the cross axis.
2. The main and cross axis depend on the flex direction.
3. If you want to modify items on the main or cross axis depending on your flex direction you need to set a `height`
4. `align-self` and `order` are some of the properties we can give to the childern.
5. `align-self` works exactly like `align-items` on the cross axis expect it modifies one single element or item/child.