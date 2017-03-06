# Container

- Container can do anything.
- So what, you might think?
- Even hot reloading
- This is awesome

```react
state:
  a: 0
  b: 10
---
<Container name={`${state.a} ~ ${state.b}`}>
  <button onClick={() => setState(({a}) => ({a: a + 1}))}>a + 1</button>
  <button onClick={() => setState(({b}) => ({b: b + 1}))}>b + 1</button>
</Container>
```

### Settings for `Container`

- `align`: `string` - left, right, center

```react
<Container align="center">
  <p>Centered contents</p>
</Container>
```
