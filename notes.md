- If we want a file to be merged in `main.scss` and not get compiled as a css file, we should add an underscore to its beginning
- On using `@use` to import a file : 
  1. There is no need to add the _ prefix
  2. We can import the file without explicitly writing its extension (similar to what webpack allows us to do)
____
- Variables follow namespaces (still to learn about it) so we need to prefix colors coming from a file with the filename (without the _ prefix)