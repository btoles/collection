# React
## Accessibility Essentials
[Semantic HTML](https://reactjs.org/docs/accessibility.html#semantic-html)

[Accessible Forms](https://reactjs.org/docs/accessibility.html#accessible-forms)
> ```<label htmlFor="namedInput">Name:</label>```
>
> Although these standard HTML practices can be directly used in React, note that the `for` attribute is **written as `htmlFor` in JSX**

[Focus Control](https://reactjs.org/docs/accessibility.html#focus-control)
> [react-aria-modal](http://davidtheclark.github.io/react-aria-modal/demo/) ~ example of good focus management

[Skip to desired content](https://reactjs.org/docs/accessibility.html#mechanisms-to-skip-to-desired-content)

[Programatically managing focus](https://reactjs.org/docs/accessibility.html#programmatically-managing-focus) ***

[Mouse and pointer events](https://reactjs.org/docs/accessibility.html#mouse-and-pointer-events)
> *...typically implemented by attaching a click event to the window object that closes the popover...*
>
> **The same functionality can be achieved by using appropriate event handlers instead, such as onBlur and onFocus**

[Other considerations](https://reactjs.org/docs/accessibility.html#other-points-for-consideration)
## Extras
[Testing accessibility in the browser](https://reactjs.org/docs/accessibility.html#testing-accessibility-in-the-browser)
* [**aXe-core**](https://github.com/dequelabs/axe-core)
* [**react-axe**](https://github.com/dequelabs/react-axe)

[Accessibility Tree](https://developer.paciellogroup.com/blog/2015/01/the-browser-accessibility-tree/)
[Commonly Used Screen Readers](https://reactjs.org/docs/accessibility.html#commonly-used-screen-readers)