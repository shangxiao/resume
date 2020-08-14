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

## Accessibility

Accessibility is something that I find extremely important.  I find that in frontend development, if we stick to basics and don't try to get too tricky we can already be well on the way to an accessible application.  Some basic things that we can do as frontend devs to help with accessibility:

* Don't disable the browser's outline feature, ie don't do: `outline: none` unless you have a suitable replacement.  http://www.outlinenone.com/
* Don't rely on mouse-only interactive elements like clickable divs.  Use a native widget like a button or an anchor styled appropriately to suit your design.
* Use form elements when creating forms.
