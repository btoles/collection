# React
## Hooks Essentials
[How to get previous props or state?](https://reactjs.org/docs/hooks-faq.html#how-to-get-the-previous-props-or-state)

[Lazy initial state](https://reactjs.org/docs/hooks-reference.html#lazy-initial-state)

[How to create expensive objects lazily?](https://reactjs.org/docs/hooks-faq.html#how-to-create-expensive-objects-lazily)
* `useState(expensiveFn(args))`
  * `expensiveFn` is run on every render even though the value is ignored after the initial render.  To avoid this, lazily create the initial state.
* `useRef` is also an open for lazy initial state.
> You might also occasionally want to avoid re-creating the useRef() initial value
>
> useRef does not accept a special function overload like useState. Instead, you can write your own function that creates and sets it lazily

[How to avoid passing callbacks down?](https://reactjs.org/docs/hooks-faq.html#how-to-avoid-passing-callbacks-down)

[Use Multiple Effects to Separate Concerns](https://reactjs.org/docs/hooks-effect.html#tip-use-multiple-effects-to-separate-concerns)



## Extras
> `useCallback(fn, deps)` is equivalent to `useMemo(() => fn, deps)`.

> `useDebugValue` can be used to display a label for custom hooks in React DevTools.
>
> See [Defer formatting debug values](https://reactjs.org/docs/hooks-reference.html#defer-formatting-debug-values)

> Re: `useEffect` dependency array "In the future, the second argument might get added automatically by a build-time transformation."