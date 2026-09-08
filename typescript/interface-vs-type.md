# Interface vs Type

| Feature             | Interface                        | Type                                               |
| ------------------- | -------------------------------- | -------------------------------------------------- |
| Purpose             | Object shapes / contracts        | Object shapes, primitives, unions, tuples, aliases |
| Declaration merging | Yes — same-name interfaces merge | No — duplicate identifier error                    |
| Extending           | `extends`                        | Intersection `&`                                   |
| Union types         | No                               | Yes                                                |
