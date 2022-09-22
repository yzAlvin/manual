# Greeting

start simple and get more complicated, do each requirement one at a time and don't peek at the next requirement

program to greet names

## Requirement 1

program that takes in a name and greets it.

eg. when `name` is `Bob`, the program outputs `Hello, Bob.`

## Requirement 2

handle nulls.

eg. when `name` is `null`, the program outputs `Hello, my friend.`

## Requirement 3

handle shouting. when a name is in all caps, the program should shout back.

eg. when `name` is `BOB`, the program outputs `HELLO BOB!`

## Requirement 4

handle two names. when `name` is a collection of names, then both names should be greeted.

eg. when `name` is `["Alice", "Bob"]`, the program outputs `Hello, Alice and Bob.`

## Requirement 5

handle an arbitrary number of names. when there are more than 2 names, separate with commas and close with `and`.

eg. when `name` is `["Alice", "Bob", "Charlie"]`, the program outputs `Hello, Alice, Bob, and Charlie.`

## Requirement 6

handle a mix of normal and all caps names. separate the output into two greetings.

eg. when `name` is `["Alice", "BOB", "Charlie"]`, the program outputs `Hello, Alice and Charlie. AND HELLO BOB!`

## Requirement 7

handle entries in `name` that contain a comma. split it and treat as a separate person to greet.

eg. when `name` is `["Charlie", "Bob, Alice"]`, the program outputs `Hello, Charlie, Bob, and Alice.`

### Source

[testdouble greeting kata](https://github.com/testdouble/contributing-tests/wiki/Greeting-Kata)