# C++ Zero Cost Conf 2025

## JSON in C++: serialization

A short talk about JSON serialization to chase down last year's talk about string escaping.
We'll quickly go through escaping as part of serialization, and why UTF-8 validation is there (we'll remind ourselves about epic fail and drama around escaping in PostgreSQL).

We'll look at serialization and discuss:
* ways to traverse elements of a JSON document using recursion;
* nuance of serializing floating point numbers;
* reporting errors, and nuances of exception types (in the context of string serialization);
* serialization of elements of unordered dictionary (associative container) in sorted order.

And a bit more.

**Video: [https://www.youtube.com/<wbr>watch?v=GKlZGbbsaVc](https://www.youtube.com/watch?v=GKlZGbbsaVc) (in Russian)**

**Slides:**
* **[PDF](JSON in C++-serialization.pdf)**
* **[PPTX](JSON in C++-serialization.pptx)**