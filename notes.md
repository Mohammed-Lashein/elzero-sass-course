- If we want a file to be merged in `main.scss` and not get compiled as a css file, we should add an underscore to its beginning
- On using `@use` to import a file : 
  1. There is no need to add the _ prefix
  2. We can import the file without explicitly writing its extension (similar to what webpack allows us to do)
____
- Variables follow namespaces (still to learn about it) so we need to prefix colors coming from a file with the filename (without the _ prefix)
____
As we can extend classes in OOP, we can extend classes but in css (in order to remove duplication and get the styles of a certain class applied by another class)
___
You can `@extend` a class, or a placeholder, but you `@include` a mixin . 
___
Regarding L8 create triangle with if and else, there is a small but an important tweak that you need to be aware of on using placeholders .   
[I wrote an article about it in arabic . ](https://www.facebook.com/share/p/18woUnn9uu/)
____
The style of commits used in this repo is called **conventional commits** . I highly encourage you to read about it .   