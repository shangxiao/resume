# Developer Profile

## Version Control Etiquette

[Semantic/Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) offer a nice way to consistently structure your version control commits in a way that helps with maintenance.

Some advantages are:
*  Separation of risk
*  Manageable chunks to review
*  Bisectability
*  Original intent discoverability
*  Deployability

I extend this theory to also require that commits be "atomic", meaning that there are certain rules as to how far you can break up commits.  Generally commits should not break things, providing some guarantees to the above features.  This includes:
*  Compileability/parseability
*  Tests
*  Features
*  Type checks
*  Optionally, lint checks
