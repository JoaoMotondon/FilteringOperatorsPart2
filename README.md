# FilteringOperatorsPart2
This project is the second part of a series of 10 articles about RxJava operators. It is related to filtering operators, but also used to avoid the need for backpressure.

Although RxJava provides some specific operators that can handle backpressure such as onBackpressureBuffer and onBackpressureDrop, this project will focus on some ordinary operators.

Here is a list of all operators available in this project:

  - sample(period)
  - sample(w/Observable)
  - throttleFirst(period)
  - debounce(timeout)
  - debounce(w/Func1)

Please, refer to [this article](http://androidahead.com/2017/09/25/rxjava-operators-part-2-more-about-filtering-operators/) for detailed information.

![Demo](https://user-images.githubusercontent.com/4574670/30805618-88922e68-a1c8-11e7-8708-b7ada85f5942.gif)

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
