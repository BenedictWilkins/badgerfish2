# badgerfish 2


Badgerfish is a convention that has been used to convert between XML and JSON data formats. The original proposal has some limitations which we aim to fix here.


### Limitation 1
In some applications the order of XML elements matters. For example, SVG elements are rendered in the order that they appear. The original badgerfish convention looses information about the order of elements when converting XML to JSON.

### Limitation 2
Text can appear at multiple places within an XML element, before and after child elements. The badgerfish syntax "$" does not support more than one instance of text.


### Goal
We want a perfect mapping from XML to JSON and back. This repository implements a converter that does this in python following a an updated scheme.

## badgerfish 2 Scheme



