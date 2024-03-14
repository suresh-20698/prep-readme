
# Shallow copy vs Deep copy

## Shallow copy

### Explanation

- Shallow copy creates a copy of an `objects` or `arrays` to new `objects` or `arrays`
- Shallow copy will create a new instance only for the top-level elements
- Nested `objects` or `arrays` are still shared between the original and the copied object or array

#### Example

- using spread operator (...)
- using object.assign method

![decode-example-image](https://i.ibb.co/fYXWYrW/Screenshot-from-2024-03-14-12-58-32.png)

## Deep copy

### Explanation

- Deep copy also creates a copy of an `objects` or `arrays` to new `objects` or `arrays`
- Deep copy will create a completely new instance for all level elements
- Deep copy will ensures that the copy is completely independent from the original one

#### Example

- using JSON.stringyfy and JSON.parse methods
- using map, filter methods

![decode-example-image](https://i.ibb.co/fYXWYrW/Screenshot-from-2024-03-14-12-58-32.png)
