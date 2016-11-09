## Synopsis

Classic fizzbuzz

if a number is divisable by 3 print fizz if divisableby 5 print buzz if divisable by both 3 + 5 print fizzbuzz. Otherwise print the number.

## Code Example

```
for (var i=1; i <= 20; i++)
{
    if (i % 15 == 0)
        console.log("FizzBuzz");
    else if (i % 3 == 0)
        console.log("Fizz");
    else if (i % 5 == 0)
        console.log("Buzz");
    else
        console.log(i);
}
```
## Motivation

stay sharp

## Contributors

Hunter Hawes
github: hunterhawes13
twitter: @tikishackfun

## License

This project is licensed under the terms of the MIT license.

## Warning

This should not be used in production. It is for demonstration purposes only.
