# Hello World DAI! 🐱‍🐉

A small maven-based test program!

### Differences with tutorial
To keep up with "recent" java standards, I did a few changes to keep up:
- As we do not own the domain, I've changed it to `knownas.red` (and as Java reverses it, we have a package name set as `red.knownas.*`)
- The logger is a static instance in the object, to keep up with standards (for classes that are acutally called multiple times, the logger creation only needs to be created a single time, instead of at each function call)