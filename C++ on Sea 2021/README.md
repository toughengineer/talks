# C++ on Sea 2021

## Fun with type erasure:<br>implementing a value wrapper for polymorphic types

The goal of this talk is to get you familiar and comfortable with the ins and outs of a basic implementation of type erasure in C++.

Using an implementation of a _value_ wrapper for polymorphic types as an example, we'll examine how type erasure works that is similar to `std::any`.

In contrast to universally used pointer or reference semantics, in this case the wrapper with value semantics allows us to treat polymorphic, type erased, objects as ordinary values: move them around, copy, and assign new values, with all the headaches of ownership and cloning handled by the implementation behind the scenes.

The _idea_ behind a value wrapper was thoroughly discussed by Jonathan Boccara in his keynote at Meeting C++ 2020 [here](https://www.youtube.com/watch?v=mU_n_ohIHQk).

**Video: [https://www.youtube.com/<wbr>watch?v=bkWpL6wEX6M](https://www.youtube.com/watch?v=bkWpL6wEX6M)**

Description on the conference site:\
[https://cpponsea.uk/<wbr>2021/<wbr>sessions/<wbr>fun-with-type-erasure-implementing-a-value-wrapper-for-polymorphic-types.html](https://cpponsea.uk/2021/sessions/fun-with-type-erasure-implementing-a-value-wrapper-for-polymorphic-types.html)

**Slides:**
* **[PDF](Fun%20with%20type%20erasure-implementing%20a%20value%20wrapper%20for%20polymorphic%20types.pdf)**
* **[PPTX](Fun%20with%20type%20erasure-implementing%20a%20value%20wrapper%20for%20polymorphic%20types.pptx)**
