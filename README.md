# Django++

*What if there existed a C++ web framework as clean, intuitive, and usable as Django?*

## Motivation

[Django](https://www.djangoproject.com) is an intuitive and beautifully designed web framework ideal for rapid web development and easy code maintenance; however, [it often leaves much to be desired in scalability](http://www.infoq.com/news/2014/05/benchmark-web-framework) unless you undertake [extensive performance tuning](https://highperformancedjango.com/).

Thus, this is an experimental project aiming to construct a very Django-like web framework...except that it's written purely in C++.

## Design Principles

Django++ is a web framework which strives to be...

  1. **Cleanly designed:**  In particular, issues of front-end display should be as strictly separated from back-end engineering as possible
  2. **Readable:** In the words of Abelson & Sussman, [programs must be written for people to read, and only incidentally for machines to execute](https://mitpress.mit.edu/sicp/front/node3.html).
  3. **Well-documented**
  4. **Easy to learn**
  5. **Not overly bloated with features**
  6. **Convenient and conducive to developer productivity, while allowing for more advanced customization and performance tuning when necessary**
  7. **Well-tested**
  8. **Performant**
  9. **Licensed for flexibility**

Notice how far down that list "performant" comes, *in spite of being a principal motivator for having embarked on this project in the first place*: **if no one can feasibly write, understand, or maintain Django++ code at scale, this project deserves rightfully to be considered a failure no matter how fast it runs.**
  
## Development

This project is currently in early-stage development, and thus should not be used in production.

Contributions are welcome, however!

## License

Copyright © 2015 Steven Das

Distributed under the Apache License 2.0.
