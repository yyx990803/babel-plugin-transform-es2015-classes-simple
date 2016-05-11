A replacement for `babel-plugin-transform-es2015-classes`, which is even looser than loose mode (removed class call check).

This is used specifically for minimal bundle size and runtime perf overhead for library internal classes - you probably want to stick to the official transform if you don't know what this entails.
