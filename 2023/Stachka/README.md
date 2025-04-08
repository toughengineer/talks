# Stachka 2023

## Fun with type erasure:<br>implementing a value wrapper for polymorphic types

The goal of this talk is to get you familiar and comfortable with the ins and outs of a basic implementation of type erasure in C++.

Using an implementation of a _value_ wrapper for polymorphic types as an example, we'll examine how type erasure works that is similar to `std::any`.

In contrast to universally used pointer or reference semantics, in this case the wrapper with value semantics allows us to treat polymorphic, type erased, objects as ordinary values: move them around, copy, and assign new values, with all the headaches of ownership and cloning handled by the implementation behind the scenes.

The _idea_ behind a value wrapper was thoroughly discussed by Jonathan Boccara in his keynote at Meeting C++ 2020 [here](https://www.youtube.com/watch?v=mU_n_ohIHQk).

Description on the conference site:\
[https://2023.nastachku.ru/<wbr>стирание-типов-в-действии-делаем-обёртку-с-семантикой-значения-для-полиморфных-типов](https://2023.nastachku.ru/%D1%81%D1%82%D0%B8%D1%80%D0%B0%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%BE%D0%B2-%D0%B2-%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D0%B8-%D0%B4%D0%B5%D0%BB%D0%B0%D0%B5%D0%BC-%D0%BE%D0%B1%D1%91%D1%80%D1%82%D0%BA%D1%83-%D1%81-%D1%81%D0%B5%D0%BC%D0%B0%D0%BD%D1%82%D0%B8%D0%BA%D0%BE%D0%B9-%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B4%D0%BB%D1%8F-%D0%BF%D0%BE%D0%BB%D0%B8%D0%BC%D0%BE%D1%80%D1%84%D0%BD%D1%8B%D1%85-%D1%82%D0%B8%D0%BF%D0%BE%D0%B2)

**Slides:**
* **[PDF](Fun%20with%20type%20erasure-implementing%20a%20value%20wrapper%20for%20polymorphic%20types.pdf)**
* **[PPTX](Fun%20with%20type%20erasure-implementing%20a%20value%20wrapper%20for%20polymorphic%20types.pptx)**