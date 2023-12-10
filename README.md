# Typescript Labs

## Lab 2: Object Params

file: `/src/02-object-param.problem.ts`

Here's a different implementation of the addTwoNumbers function:

```ts
export const addTwoNumbers = (params) => {
  return params.first + params.second;
};
```

This time the function accepts a params object with first and second properties.

{
  first: 2,
  second: 4,
}

Similarly to last time, we're getting the "implicitly has an 'any' type" error.


**_challenge_**: Work out how to type params as an object with a key of `first` that is a number and a key of `second` that is also a number.
