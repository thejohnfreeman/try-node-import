How must we configure package A to let package B import submodules of package
A?

This project has package A in directory `a`, and different kinds of package
B in directories prefixed with `b-`: CommonJS, ES module, and TypeScript.
Each package B has a dependency on package A through a Yarn `link:` package
specification, and is thus meant to be bootstrapped using Yarn.
