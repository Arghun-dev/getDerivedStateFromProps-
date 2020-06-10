# getDerivedStateFromProps

```
static getDerivedStateFromProps(props, state)
```

### When to Use Derived State

getDerivedStateFromProps exists for only one purpose. It enables a component to update its internal state as the result of changes in props. Our previous blog post provided some examples, like recording the current scroll direction based on a changing offset prop or loading external data specified by a source prop.
