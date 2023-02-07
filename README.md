# shapeprop
A [Package](https://pypi.org/project/shapeprop/0.1.0/) to Explore Shape Properties

## Installation

pip install shapeprop

## Usage

#### Find the area of a circle given the radius.

```
PS F:\Github\shapeprop> python
Python 3.10.6 (tags/v3.10.6:9c7b4bd, Aug  1 2022, 21:53:49) [MSC v.1932 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> from shapeprop.circle.shape import area
>>> myarea = area(10)
>>> myarea
314.1592653589793
```

#### Find the perimeter of a triangle given the lengths of three sides.

```
PS F:\Github\shapeprop> python
Python 3.10.6 (tags/v3.10.6:9c7b4bd, Aug  1 2022, 21:53:49) [MSC v.1932 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> from shapeprop.triangle.shape import perimeter
>>> tp = perimeter(10, 9, 17)
>>> tp
36
```
