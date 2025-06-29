
# app

* application refers to any software application built using the Node.js runtime environment.
### favicon.ico

* We can see the top on the webpage a small icon.

### globals.css

* a file where you can define CSS styles that are applied globally across your entire application. 

## node_modules

* We store all the installed packages. 
* Use packages in our Node.js code.
* Automatically generated, and we should not modify it manually.

## Public
* Static files like images, icons, fonts, or frontend assets.

## .gitignore

* .gitignore is a text file in our Git repository that tells Git which files to ignore in a project.

## eslint.config.mjs

* ESLint project configuration in a configuration file.
*  ESLint a tool that checks for JavaScript errors and enforces coding style.

## jsconfig.json

*  jsconfig.json file is a configuration file used in JavaScript projects and TypeScript is a optional.
## package-lock.jason and package.json

* package-lock.json locks down the specific versions of all packages. It is automatically created and maintained by npm. 
* we should not modify it manually.

NPM - Node Package Manager

* used for installing and publishing packages 

NPE - Node Package Execute

* NPX is a package executer without installing we can use dirctly.
==================================================

# Tailwindcss


### Styling with utility classes

* Tailwind classes are short and reusable CSS utility names used directly in HTML to style elements.

### Font-size:

* Controlling the font size of an element `text-base`.
* we can change line-height of an element at the same time `text-xl/6`.

### Color:

* Controlling the color of an element `text-red-700`.

### Font-weight:

* controlling the font weight of an element `font-[<value>]`.

### Gap:

* The utilities for controlling gutters between grid and flexbox items `gap-<number>`.

### Width and Height:

* utilites for setting the width and height of an element `w-<number>` `w-<number> ` `w-sm` `w-[<value>]` `h-<number>` `h-full` `h-dvh` `h-lvh` `h-svh`.
* we can use number,percentage,container scale. 

### Background-color:

* controlling an element's background color `bg-white` `bg-[<value>]`.

**Opacity**
* the color opacity modifier to control the opacity of one element's background color.

**hover**

* prefix a `background-color` utility with a variant like `hover:*` to only apply the utility in that state.

**custom value**

* To set the background color based on a completely custom value.`bg-[<value>]`

**Border-radius**

* We can apply different border radius sizes to an element.
`rounded-sm` `rounded-md` `rounded-xl` `rounded-lg`
* Only rounding one side of an element.`rounded-t-lg` `rounded-r-lg` `rounded-b-lg` `rounded-l-lg`
* only rounding one corner of an element.
`rounded-tl-lg` `rounded-tr-lg` `rounded-br-lg` `rounded-bl-lg`
* Create pill buttons `rounded-full`.
* Removing the border radius `rounded-none`.
* To set the border radius based on a completely custom value `rounded-[<value>]`.


### box-shadow

* To apply different sized outer box shadows to an element.  `shadow-md` `shadow-lg` `shadow-xl`

* We use opacity modifier to adjust the opacity of the box shadow.`shadow-xl/20` `shadow-xl/30`

#### shadow color

* To change the color of a box shadow.`shadow-indigo-500` `shadow-cyan-500/50` 
* By default colored shadows have an opacity of 100% but We can adjust this using the opacity modifier.

### inset shadow

* To apply an inset box shadow to an element. `inset-shadow-2xs` `inset-shadow-xs` `inset-shadow-sm`
* We can adjust the opacity of an inset shadow using the opacity modifier `inset-shadow-sm/50` and The default inset shadow opacities 5%, Increasing the opacity to like 50% will make the inset shadows more pronounced.

###  inset shadow color

* To change the color of an inset box shadow. `inset-shadow-indigo-500` `inset-shadow-cyan-500/50`
* By default colored shadows have an opacity of 100% but We can adjust this using the opacity modifier.

### Adding a ring

* To apply a solid box-shadow to an element.`ring-<number>`
* We can modifiy `ring-2` `ring-4` `ring`.
* By default rings match the currentColor of the element applied.

### ring color

* To change the color of a ring.`ring-2 ring-blue-500` `ring-2 ring-blue-500/50 `, By default rings have an opacity of 100% but We can adjust this using the opacity modifier.

###  inset ring

* To apply a solid inset box-shadow to an element.`inset-ring-<number>` `inset-ring-2`
* By default inset rings match the currentColor of the element they are applied.


### inset ring color

* To change the color of an inset ring.
`inset-ring-2 inset-ring-blue-500` `inset-ring-cyan-500/50`
* The default inset rings have an opacity of 100% but We can adjust this using the opacity modifier.

### box shadow

* To remove an existing box shadow from an element. `hadow-none` `inset-shadow-none` `inset-ring-0`

# max-width

* To set an element to a fixed maximum width based on the spacing scale. `max-w-<number>` `w-full max-w-24`

###  percentage

* To give an element a percentage-based maximum width.`max-w-full` `w-full max-w-9/10`

### container scale

* To set an element to a fixed maximum width based on the container scale. `max-w-sm` auto center->`mx-auto`

# margin

* To control the margin on all sides of an element.
`m-<number>` `m-4`

###  margin to a single side

* To control the margin on one side of an element. `mt-<number>` `mr-<number>` `mb-<number>` `ml-<number>`

### horizontal margin

* To control the horizontal margin of an element. `mx-<number>` `mx-4`

### vertical margin

* To control the vertical margin of an element. `my-<number>` `my-4`

### space between children

* To control the space between elements. `space-x-<number>` `space-y-<number>` `flex space-x-4 `

### children order

* To ensure the space is added to the correct side of each element. `space-x-reverse` `space-y-reverse` If your elements are in reverse order.`flex-row-reverse` or `flex-col-reverse`


# display

### Block and Inline

* To control the flow of text and elements. `inline` `inline-block` `block`
* `inline` Inline will cause the text inside the element to wrap normally.
* `inline-block` The element to prevent the text inside from extending beyond its parent.
* `block` The element on its own line and fill its parent.

### Flex

* To create a block-level flex container.`flex`

### inline-flex

* To create an inline flex container that flows with text.
`inline-flex`


### Grid

* To create a grid container.`grid`

### Inline Grid

* To create an inline grid container.`inline-grid`

### Contents

* To createcontainer whose children act like direct children of the parent.`contents`


### Table

* To create elements that behave like their respective table elements. `table`, `table-row`, `table-cell`, `table-caption`, `table-column`, `table-column-group`, `table-header-group`, `table-row-group`, `table-footer-group` 


### Hidden

* To remove an element from the document. To visually hide an element but keep it in the document. `hidden`

### Screen-reader only

* `sr-only` to hide an element visually without hiding it from screen readers.

* `not-sr-only` to undo `sr-only`, making an element visible to sighted users as well as screen readers.

* This can be useful when you want to visually hide something on small screens but show it on larger screens.


# Padding

* `p-<number>` To control the padding on all sides of an element.

### Adding padding to one side

* To control the padding on one side of an element.`pt-<number>`, `pr-<number>`, `pb-<number>`,`pl-<number>`

### horizontal padding

* To control the horizontal padding of an element.`px-<number>`

### vertical padding

* To control the vertical padding of an element.`py-<number>`

# Hover, focus, and other states

* Adding a variant to the beginning of the class name that describes the condition you want to target.

* To apply the `bg-sky-700` class on hover, use the `hover:bg-sky-700` class.

### :hover, :focus, :active

* The Style elements on hover, focus, and active using all the hover, focus, and active variants.

* Tailwind variants for other interactive states like `:visited`, `:focus-within`, `:focus-visible`, and more.

### :first, :last, :odd, :even

* We add Style an element when it is the first-child or last-child using the first and last variants.

* We use the nth-* and nth-last-* variants to style children based on their position in the list

* We use arbitrary values for more complex expressions like `nth-[2n+1_of_li]`.

* Tailwind also includes variants for other structural pseudo-classes like `:only-child`, `:first-of-type`, `:empty`, and more.

# Pseudo-class

* The examples for all the pseudo-class variants. 

### hover:

* The `hover:` variant is used to apply styles when the user hovers over an element.

### focus:

* We Style an element when it has focus using the `focus`
variant.

### focus-within:

* We Style an element when one of its descendants has focus using the `focus-within` variant.

### focus-visible:

* Element when it has been focused using the keyboard using the `focus-visible`.

### active:

* element when it is being pressed using the `active` variant.

### visited:

* A link when it has already been visited using the `visited` variant.

### target:

*  An element if its ID matches the current URL fragment using the target.

### first-child:

* An element if it's the first child using the `first` variant.

### last-child:

* An element if it's the last child using the `last` variant.

### only-child:

* An element if it's the only child using the `only` variant.

### nth-child(odd):

* An element if it's an oddly numbered child using the `odd` variant.

### nth-child(even):

* An element if it's an evenly numbered child using the `even` variant.

### first-of-type:

* An element if it's the first child of its type using the `first-of-type` variant.

### last-of-type:

* An element if it's the last child of its type using the `last-of-type` variant.

### only-of-type:

* An element if it's the only child of its type using the `only-of-type` variant.

### nth-child():

* We style an element at a specific position using the `nth` variant.

### nth-last-child():

* We style an element at a specific position from the end using the `nth-last` variant.

### nth-of-type():

* We style an element at a specific position, of the same type using the `nth-of-type` variant.

### nth-last-of-type():

* We style an element at a specific position from the end, of the same type using the `nth-last-of-type` variant.

### empty:

* An element if it has no content using the `empty` variant.

### disabled:

* We style an input when it's disabled using the `disabled` variant.

### enabled:

* We style an input when it's enabled using the `enabled` variant, most helpful when you only want to apply another style when an element is not disabled.

### checked:

* Checkbox or Radio button when it's checked using the `checked` variant.

### indeterminate:

* We style a checkbox or radio button in an indeterminate state using the `indeterminate` variant.

### default:

* Checkbox or radio button that was the default value when the page initially loaded using the `default` variant.

### optional:

* An input when it's optional using the `optional` variant.

### required:

* Input when it's required using the `required` variant.

### valid:

* We style an input when it's valid using the `valid` variant.

### invalid:

* We style an input when it's invalid using the `invalid` variant.

### user-valid:

* We style an input when it's valid and the user has interacted with it, using the `user-valid` variant.

### user-invalid:

* We style an input when it's invalid and the user has interacted with it, using the `user-invalid` variant.

### in-range:

* We style an input when its value is within a specified range limit using the `in-range` variant.

### out-of-range:

* We style an input when its value is outside of a specified range limit using the `out-of-range` variant.

### placeholder-shown:

* We style an input when the placeholder is shown using the `placeholder-shown` variant.

### details-content:

* We style the content of a `details` element using the `details-content` variant.

### autofill:

* An input when it has been autofilled by the browser using the `autofill` variant.

### read-only:

* Style an input when it is read-only using the `read-only` variant.

## has():

* We use the  `has-*` variant to style an element based on the state or content of its descendants.

## peer:

* If we need to style an element based on the descendants of a sibling element, We can mark the sibling with the `peer` class and use the `peer-has-*` variant to style the target.


## not():

* We use the `not-` variant to style an element when a condition is not true.

* When we combining `not-focus:` with `hover:` to only apply hover styles when an element is not focused.

* We combine the `not-` variant with media query variants like `forced-colors` or `supports`.

### We Styling based on parent state

* When you need to style an element based on the state of some parent element, mark the parent with the `group` class, and use `group-*` variants like `group-hover` to style the target element.

* This pattern works with every pseudo-class variant, for example `group-focus`, `group-active`, or even `group-odd`.

### Differentiating nested groups

* We can style something based on the state of a specific parent group by giving that parent a unique group name using a `group/{name}` class, and including that name in variants using classes like `group-hover/{name}`.

### Differentiating peers

* When using multiple peers, you can style something on the state of a specific peer by giving that peer a unique name using a `peer/{name}` class, and including that name in variants using classes like `peer-checked/{name}`.

## Pseudo-elements

#### ::before and ::after

* We style the `::before` and `::after` pseudo-elements using the before and after variants.

* The `::before` pseudo-element can be used to insert content before the content of an element. It is often used to add decorative content or icons.

* The `::after` pseudo-element can be used to insert content after the content of an element. It is often used to add decorative content or to clear floats. 

### ::placeholder

* The Style the placeholder text of any input or textarea using the `placeholder` variant.

### ::file

* We style the button in file inputs using the `file` variant.

### ::marker

* We style the counters or bullets in lists using the `marker` variant.

* It is used to style the marker box of a list item 
(i.e., the bullet points or numbers). 

### ::selection

* Style the active text selection using the `selection` variant.

### ::first-line and ::first-letter

* We style the first line in a block of content using the `first-line` variant, and the first letter using the `first-letter` variant.


### ::backdrop

* We style the backdrop of a native dialog element using the backdrop variant.

### forced-colors

* We use the `forced-colors` variant to conditionally add styles when the user has enabled a forced color mode.

### inverted-colors

* Use the `inverted-colors` variant to conditionally add styles when the user has enabled an inverted color scheme.

### pointer and any-pointer

* `pointer` media query tells you whether the user has a primary pointing device, like a mouse, and the accuracy of that pointing device.

* Use the `pointer-fine` variant to target an accurate pointing device, like a mouse or trackpad.

* We can use `pointer-none` and `any-pointer-none` to target the absence of a pointing device.

### orientation

* We use the `portrait` and `landscape` variants to conditionally add styles when the viewport is in a specific orientation.

### scripting

* Use the noscript variant to conditionally add styles based on whether the user has scripting.

## print

* `print` variant to conditionally add styles that only apply when the document is being printed.

## @supports

* Use the `supports-[...]` variant to style things based on whether a certain feature is supported in the user's browser.

## @starting-style

* Use the `starting` variant to set the appearance of an element when it is first rendered in the DOM.

## Dark mode

* it's becoming more common to design a dark version of our website to go along with the default design.

* `dark` variant that lets you style your site differently when dark mode is enabled.

## Theme variables

* Theme variables are special CSS variables defined using the `@theme` directive that influence which utility classes exist in our project.

* We can add a new color to our project by defining a theme variable like `--color-mint-500`. We can classes like bg-mint-500, text-mint-500, or fill-mint-500 in your HTML.

## color

* We can apply colors in Tailwind, which uses utility classes to handle colors.

#### color utilities

 * We use color utilities like `bg-white`, `border-pink-300`, and `text-gray-950` to set the different color properties of elements in our design color.

 
### Utility_________________ Description
   * bg-*	------------------Sets the background color of an element
   * text-* ------------------Sets the text color of an element
   * decoration-* ------------Sets the text decoration color of an element
   * border-*	--------------Sets the border color of an element
   * outline-*	--------------Sets the outline color of an element
   * shadow-*	--------------Sets the color of box shadows
   * inset-shadow-*	----------Sets the color of inset box shadows
   * ring-*	------------------Sets the color of ring shadows
   * inset-ring-*	----------Sets the color of inset ring shadows
   * accent-*	--------------Sets the accent color of form controls
   * caret-*	--------------Sets the caret color in form controls
   * fill-*	------------------Sets the fill color of SVG elements
   * stroke-*	--------------Sets the stroke color of SVG elements
