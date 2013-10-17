# Custom element
It is a new, custom DOM element. It lets you create new markups in your documents, adding semantic. By using custom elements you can avoid the infamous `div soup` where most divs are there exclusively for presentation. Custom Elements are part of a bigger whole, Web Components. Together with Shadow DOM and Templates, they offer very powerful features for reusability and encapsulation.

# Type extensions
Custom elements can be shiny new HTML tags, or just extensions of existings tag. If you are creating a new awesome table, then you can extend the origin HTMLTableElement and inherit all its features. If the browser does not recognize the custom tag, it will interpret it as its original base type, making your component beautifully degradable.

# Div soup
It refers to a heavy nesting of divs with no added semantic value. A div soup is often a result of tying presentational logic to DOM elements. Not only does it decrease the overall performance of the application, it makes the markup hard to read and understand; both for a human or a web-crowler. The Shadow DOM addresses this problem by hiding away the div soup, treating it as an implementation detail.

# Lifecycle callbacks

# FOUC (Flash Of Unstyled Content)

# Polymer

# x-tag

# Polyfill

# Pseudo-classes
They are a category of CSS selectors. They describe a special state of a selector. This state is often due to external factors, such as a :hover, or a :visited state. It's like a class, but added by your browser.

# Pseudo-elements
Like its name implies, they target elements that aren't really elements, such as the first letter of a paragraph, or the current selection. With Web Components and Custom Elements, it is possible to open parts of your components for styling. The mechanism used for it is through pseudo-elements. Note that the Shadow DOM offers `::distributed()` the first ever functional pseudo-element.

# at-rules

# HTML Imports

# Insertion point (<content></content)

# Shadow insertion point

# Distributed nodes
Nodes that have been selected by a content element in the Shadow DOM are called distributed nodes.

# Shadow Root
It is the root of the Shadow Tree. An HTMLElement can decide to host a Shadow Tree. If it's the case, then a Shadow Root must be declared on that HTMLElement. To represent Shadow Roots, a DocumentFragment is used. It is possible to inspect the Shadow Dom on the Chrome Dev Tools by turning on an option in the parameters.

# Younger tree
A DOM Node can have multiple Shadow Trees. The last one created is called the youger tree.

# Older tree
As opposed to the Younger Tree, the Older Tree refers to the first Shadow Tree created.

# Shadow Tree
Its the tree whose root is the Shadow Root. It is self contain, so it doesn't leak or have access to the outer DOM. Any style applied to the Shadow Tree will be encapsulated for that tree.