# ACCU 2022

## Fun with type erasure<br>+ dispatching data from abstract structure to function parameters in C++

Sometimes we want some kind of magic that would call appropriate handler for a request, and put appropriate request fields into function parameters, e.g.:
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
(That is, in this C# example, for request "baz" we want the function `baz` to be called, and values of fields "count", "id" and "payload" to be passed to corresponding function parameters.)

We want this magic even more when the number of handlers with many parameters grows significantly.
In this talk we will concentrate on type erasure in C++ in order to make convenient and user friendly way of organizing request handlers.

We will examine several approaches, their profit, how can we make it better, and what else can we do with it. There will be a lot of code. (And template magic, you just can't do anything without it.)

**Demos are [here](demo.md).**

**Video: [https://www.youtube.com/<wbr>watch?v=e3GcXIHL8NA](https://www.youtube.com/watch?v=e3GcXIHL8NA)**

**Slides:**
* **[PDF](Fun%20with%20type%20erasure+dispatching%20data%20from%20abstract%20structure%20to%20function%20parameters%20in%20C++.pdf)**
* **[PPTX](Fun%20with%20type%20erasure+dispatching%20data%20from%20abstract%20structure%20to%20function%20parameters%20in%20C++.pptx)**
