JavaScript Inheritance Patterns
---

## Objectives

1. Explain how prototypal inheritance works in JavaScript
2. Practice inheriting from prototypes with `Object.create()`
3. Explain how to use `hasOwnProperty()`

## Introduction

- Frame the narrative by talking about objects in the real world. I know animals/cars are classic examples, but they're also problematic (to wit: https://cdn-images-1.medium.com/max/1600/1*Gxyrlu41qHNbZAPdoxR7_w.jpeg). Better, maybe, is a more abstract class -- polygons are great for this:
  - Polygon(sides:number) => Quadrilateral(top:number,right:number,bottom:number,left:number) => Rectangle(side_length1:number,side_length2:number) => Square(side_length:number)

## Inheritance

- Walk students through using `Object.create()`: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create
- Build on the shapes example
- Use animals if necessary

## hasOwnProperty()

- Make students "feel the pain" -- iterate through an object's properties and show that stuff is in there that shouldn't be (if it has inherited from another object)

- Show students how to use `hasOwnProperty()` to avoid these issues

## Resources

- [Object.create()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)
