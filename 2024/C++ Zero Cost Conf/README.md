# C++ Zero Cost Conf 2024

## JSON in C++: escaping and serialization

Using JSON escaping as a context we will explore:
* UTF-8, Unicode, and minimal implementation to support them (a.k.a. what you need to know but maybe don't);
* how to account for different implementations using `contexpr` (considering performance).

Looking at JSON serialization/stringification we'll touch:
* ways to iterate over elements in JSON document with account for recursion;
* nuance of serializing floating point numbers;
* error reporting and nuances of exception types (in the context of serializing strings);
* serializing elements of unordered map in sorted order.

And a bit more.

**Video: [https://www.youtube.com/<wbr>watch?v=1THwOpon4vg](https://www.youtube.com/watch?v=1THwOpon4vg)**

**Slides:**
* **[PDF](JSON in C++-escaping and serialization.pdf)**
* **[PPTX](JSON in C++-escaping and serialization.pptx)**