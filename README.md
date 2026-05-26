# ERGM Method Selector

An interactive, click-through guide for choosing an exponential random graph
model (ERGM) specification. Answer a short sequence of questions and the page
routes you to a single recommended method — with the dependence assumption,
what to specify, how to estimate, how to check fit, and which software to use.

Each recommendation also includes:

- **Starter code** — a copy-paste R (`statnet`/`ergm`, or `tergm` for
  longitudinal models) scaffold for that exact specification, with a copy
  button. It is a starting point to adapt to your own data, not a script to run
  as-is.
- **Term tooltips** — key terms (GWESP, social-circuit, dyadic independence,
  degeneracy, MCMC-MLE, triad census, and others) are dotted-underlined; hover
  or tap them for a plain-language definition.

Based on Lusher, Koskinen & Robins (eds.), *Exponential Random Graph Models for
Social Networks: Theory, Methods, and Applications* (Cambridge University Press, 2013).