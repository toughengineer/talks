# C++ on Sea 2022

## Understanding C++ coroutines by example,<br>[part 1](#part1) and [part 2: generators](#part2-generators)

Coroutines are a powerful tool added to C++20. There are no out-of-the-box facilities in the standard library that are user friendly and immediately usable, although there are plenty of libraries out there already providing such primitives.

Also there are now best practices regarding usage of coroutines in C++ that emerged while people were learning them, and that programmers should know about.

### <a name="part1"></a>Part 1

There is a chance standard primitives will be added to C++23 so all the machinery will be "hidden" from the user, though there's still value in learning how it works under the hood. So we’ll be doing just that.

We’ll figure out how to use coroutines _from the ground up_ by example of how to work with asynchronous tasks. You'll learn about `co_await` and `co_return` keywords, "magical" transformations of coroutine code done by the compiler, and some basic challenges and best practices.

Description on the conference site:\
[https://cpponsea.uk/<wbr>2022/<wbr>sessions/<wbr>understanding-cpp-coroutines-by-example-<wbr>part-1-online.html](https://cpponsea.uk/2022/sessions/understanding-cpp-coroutines-by-example-part-1-online.html)

**Video: [https://www.youtube.com/<wbr>watch?v=tj0URCY_A1s](https://www.youtube.com/watch?v=tj0URCY_A1s)**

**Slides:**
* **[PDF](Understanding%20C++%20coroutines%20by%20example%201.pdf)**
* **[PPTX](Understanding%20C++%20coroutines%20by%20example%201.pptx)**

### <a name="part2-generators"></a>Part 2: generators

This time we will concentrate on the _generators_ part of the coroutines.  
We'll get up to speed with how coroutines work under the hood, and then learn about the `co_yield` keyword, and how simple generators and asynchronous generators conceptually work.

Description on the conference site:\
[https://cpponsea.uk/<wbr>2022/<wbr>sessions/<wbr>understanding-cpp-coroutines-by-example-<wbr>part-2-generators-online.html](https://cpponsea.uk/2022/sessions/understanding-cpp-coroutines-by-example-part-2-generators-online.html)

**Video: [https://www.youtube.com/<wbr>watch?v=9p7obE9KRoU](https://www.youtube.com/watch?v=9p7obE9KRoU)**

**Slides:**
* **[PDF](Understanding%20C++%20coroutines%20by%20example%202-generators.pdf)**
* **[PPTX](Understanding%20C++%20coroutines%20by%20example%202-generators.pptx)**
