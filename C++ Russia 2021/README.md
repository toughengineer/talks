# C++ Russia 2021

## Fun with type erasure<br>+ dispatching data from abstract structure to function parameters

Sometimes we want some kind of magic that would call the appropriate handler for a request, and put appropriate request fields into function parameters, e.g.:
```json
{
  "request": "baz",
  "count": 1,
  "id": "two",
  "payload": { "three": 3 }
}
```
↓
```cs
public class Program
{
  public static void foo()
  { }
  public static void bar([Name("count")] int i)
  { }
  public static void baz([Name("count")] int i,
                         [Name("id")] string s,
                         [Name("payload")] JsonElement p)
  { }
} 
```
We want this magic more when the number of handlers with many parameters grows significantly.

In this talk, we will concentrate on type erasure to make a convenient and user-friendly way of organizing request handlers.\
We will examine several approaches, their profit, how we can make it better, and what else we can do with it. Warning: there will be a lot of code.

**Demos are [here](demo.md).**

**Video: [https://www.youtube.com/<wbr>watch?v=u4_JAn83FJQ](https://www.youtube.com/watch?v=u4_JAn83FJQ)**

Description on the conference site:\
[https://cppconf.ru/<wbr>en/<wbr>talks/<wbr>fun-with-type-erasure-dispatching-data-from-abstract-structure-to-function/](https://cppconf.ru/en/talks/fun-with-type-erasure-dispatching-data-from-abstract-structure-to-function/)\
(and [in Russian](https://cppconf.ru/talks/fun-with-type-erasure-dispatching-data-from-abstract-structure-to-function/))

**Slides:**
* **[PDF](Fun%20with%20type%20erasure+dispatching%20data%20from%20abstract%20structure%20to%20function%20parameters.pdf)**
* **[PPTX](Fun%20with%20type%20erasure+dispatching%20data%20from%20abstract%20structure%20to%20function%20parameters.pptx)**
