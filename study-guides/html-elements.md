<<<<<<< HEAD
=======

>>>>>>> b1a19b589f81bdf0409bdde406873c563edf994d
## Common HTML Elements

## Defining HTML Elements

In order to add elements to our website, we add HTML tags. There are many different types of tags that represent different types of elements (i.e text, images, buttons, containers, etc.).

![Image of different phases of lego illustrating HTML, CSS, and JS](https://user-images.githubusercontent.com/5963600/108429318-c890b480-720d-11eb-8e49-cbe2de42c596.png)

An HTML tag has 3 major components:

- **Opening Tag**: The opening tag identifies the type of HTML element. The element name between the `<>` symbols. To customize an HTML element, attributes may also be defined within the opening tags. Attributes may give the element properties that include the width, size, class or id selectors, style, etc. You can read more about various [HTML element attributes on MDN Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes).
- **Contents**: This is the information that you want displayed. Depending on the type of elements the contents can be text that is visible to the user or other nested HTML elements for container-like elements.
- **Closing Tag**: The closing tag must be identical to the opening tab with the use of a backslash `\` symbol to denote the closing tag. It contains the name of the element between the `</>` symbols.
In order for our style sheet, or CSS file, to identify the different `div` sections, we use custom selectors. This is where attributes like `id` and `class` come in!

- `id` attribute: An id is a name that is  unique to an element. This means that no two elements can share the same `id`.
- `class` attribute: Unlike the `id` attribute, multiple elements can share the same `class` name. This can be helpful when styling similar types of sections or elements.

We will explore more about the CSS syntax used to apply styling to `id` and `class` names in the next section. For now, let’s set up the structure of our client’s personal website based on our wireframe.