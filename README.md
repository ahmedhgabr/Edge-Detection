# Edge-Detection
The main aim of this script is to experiment with scale invariant feature detectors, the
case of edge detection. First-derivative-based edge detectors work mainly
by, first, defining a score coefficient for both partial differentials, x and y, then calculating a
magnitude based on them. As each of the partial differentials are calculated based on kernel
convolution, there is a high level of sensitivity/dependence on the size of the kernel used. In
other words, based on the size of the kernel, some features can be detected with a margin
accuracy which is higher than others. Hence, an experiment on the scale invariance is to be
conducted in this assignment.
| Input | Output |
| ------| -------|
| ![input](https://github.com/user-attachments/assets/179149f0-4301-449a-9f2a-1fb356bc3267) | ![output](https://github.com/user-attachments/assets/8cb954f3-29d7-4042-b5a5-c82baf1c677b) |
