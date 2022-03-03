# Optimization Methods

This repo contains a series of notebooks demonstrating optimization techniques using [Google OR Tools](https://developers.google.com/optimization/introduction/overview) optimization software.

The goal is to motivate the need for such tools and demonstrate how they operate.

I'm beginning with the Linear Programming module.

OR Tools is available in [Python](https://developers.google.com/optimization/install), [C++](https://developers.google.com/optimization/install/cpp), [C#](https://www.nuget.org/packages/Google.OrTools/9.2.9972?_src=template), and [Java](https://developers.google.com/optimization/install/java).

The Python package can be installed with PIP
```python
pip install ortools
```

The .Net version can be package referenced with NuGet
```
dotnet add package Google.OrTools --version 9.2.9972
```

It can also be referenced in .Net Interactive via
```c#
#r "nuget: Google.OrTools, 9.2.9972"
```
