# JavaScript: Triangle

Write a program that can tell you if a triangle is equilateral, isosceles, or scalene.

The program should raise an error if the triangle cannot exist.

## Hint

The triangle inequality theorem states:
z ≤ x + y
where x,y, and z are the lengths of the sides of a triangle. In other words, the
sum of the lengths of any two sides of a triangle always exceeds or is equal to
the length of the third side.

A corollary to the triangle inequality theorem is there are two classes of
triangles--degenerate and non-degenerate. If the sum of the lengths of any two
sides of a triangle is greater than the length of the third side, that triangle
is two dimensional, has area, and belongs to the non-degenerate class. In
mathematics, a degenerate case is a limiting case in which an element of a class
of objects is qualitatively different from the rest of the class and hence
belongs to another, usually simpler, class. The degenerate case of the triangle
inequality theorem is when the sum of the lengths of any two sides of a triangle
is equal to the length of the third side. A triangle with such qualities is
qualitatively different from all the triangles in the non-degenerate class since
it is one dimensional, looks like a straight line, and has no area. Such
triangles are called degenerate triangles and they belong to the degenerate
class.

## Dig Deeper

This exercise does not test for degenerate triangles. Feel free to add your own
tests to check for degenerate triangles.

These tests use jasmine-node, which is a testing framework written for Node.js.

You will need:

* Node.js
* The Node Package Manager (NPM)
* jasmine-node

You can install both Node.js and NPM with a download from nodejs.org: https://nodejs.org/en/download

Use NPM to install jasmine-node:

    npm install jasmine-node -g

To work on an exercise, change to the directory of the exercise:

    cd hello-world

This contains the files for the exercise.

    .
    ├── README.md
    └── hello-world.spec.js

To run a test file, pass it as an argument to the `jasmine-node` command:

    jasmine-node hello-world.spec.js

## Source

The Ruby Koans triangle project, parts 1 & 2 [http://rubykoans.com](http://rubykoans.com)

This exercise is from the [JavaScript][javascript] track on [Exercism][exercism]

[exercism]: http://exercism.io
[javascript]: http://exercism.io/languages/javascript



