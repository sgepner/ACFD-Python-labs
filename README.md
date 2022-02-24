# ACFD Python labs

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sgepner/ACFD-Python-labs.git/main)

This contains a set of laboratories designed for students of the ACFD class.

1. Linear 1D advection problem solved with different discretizations with the focus on stability and manifestation of the numerical error.
  * Start with the **time explicit** scheme and show that the application of the **central 2'nd order** scheme for the spacial derivative yelds an unstable method - comment on the origin of the instability. This should have been covered on MOMP.
  * Change the spacial sheme to the fisrst order. Show two possibile choices the down- and up wind. One is going to be unstable. Try to explain why.
  * The upwinding, first order sheme is stable, but in consequence of the used discretization (shown in the lecture) there is a numerical error which manifests as an additional diffusive part. Show it.
  * Now change to the time implicit scheme. Explain that now stability of the central scheme is possible. But there is a change in the way numerical error manifests - numerical diffusion.
  * Other problems?
2. 1D Burgers equation as an example of a nonlinear problem. Students should by this time be able to solve the Burgers equation with the use of the method of characteristics. What they do not know is how to handle this problem numerically.
  * Write the Burgers equation in the conservative and non-conservative form. Attempt a simple discretization approach and verify the solution with the analitycal one.
  * Test propagation of the discontinuity. There should be differences resulting from the scheme used.
3. 1D Euler equation. We consider a selected discretization method and a possible time advancment for the nonlinear problem.
