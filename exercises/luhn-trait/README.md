# Luhn Trait

# Luhn: Using a Custom Trait

Before doing this exercise you should probably do the original Luhn exercise and its successor, "Luhn: Using the From Trait"

To get the original Luhn exercise, run

```shell
exercism download --exercise=luhn --track=rust
```

To get the "Luhn: Using the From Trait" exercise, run

```shell
exercism download --exercise=luhn-from --track=rust
```

In the original Luhn exercise you only validated strings, but the Luhn algorithm can be applied to integers as well.

In "Luhn: Using the From Trait" you implemented a From trait, which also required you to create a Luhn struct.

Instead of creating a Struct just to perform the validation, what if you validated the primitives (i.e, String, u8, etc.) themselves?

In this exercise you'll create and implement a custom [trait](https://doc.rust-lang.org/book/ch10-02-traits.html) that performs the validation.

Note: It is [not idiomatic Rust to implement traits on on primitives](https://doc.rust-lang.org/book/ch10-02-traits.html#implementing-a-trait-on-a-type). In this exercise we're showing something that you _can_ do, not something you _should_ do. If you find yourself implementing traits on primitives, perhaps you have a case of [Primitive Obsession](http://wiki.c2.com/?PrimitiveObsession).

## Rust Installation

Refer to the [exercism help page][help-page] for Rust installation and learning
resources.

## Writing the Code

Execute the tests with:

```bash
$ cargo test
```

All but the first test have been ignored. After you get the first test to
pass, open the tests source file which is located in the `tests` directory
and remove the `#[ignore]` flag from the next test and get the tests to pass
again. Each separate test is a function with `#[test]` flag above it.
Continue, until you pass every test.

If you wish to run all tests without editing the tests source file, use:

```bash
$ cargo test -- --ignored
```

To run a specific test, for example `some_test`, you can use:

```bash
$ cargo test some_test
```

If the specific test is ignored use:

```bash
$ cargo test some_test -- --ignored
```

To learn more about Rust tests refer to the [online test documentation][rust-tests]

Make sure to read the [Modules](https://doc.rust-lang.org/book/ch07-00-modules.html) chapter if you
haven't already, it will help you with organizing your files.

## Feedback, Issues, Pull Requests

The [exercism/rust](https://github.com/exercism/rust) repository on GitHub is the home for all of the Rust exercises. If you have feedback about an exercise, or want to help implement new exercises, head over there and create an issue. Members of the rust track team are happy to help!

If you want to know more about Exercism, take a look at the [contribution guide](https://github.com/exercism/docs/blob/master/contributing-to-language-tracks/README.md).

[help-page]: https://exercism.io/tracks/rust/learning
[modules]: https://doc.rust-lang.org/book/ch07-00-modules.html
[cargo]: https://doc.rust-lang.org/book/ch14-00-more-about-cargo.html
[rust-tests]: https://doc.rust-lang.org/book/ch11-02-running-tests.html

## Source

The Rust track maintainers, based on the original Luhn exercise

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.
