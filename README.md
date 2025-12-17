# XRDplayground

**XRD Playground** is a software tool that calculates the powder X-Ray Diffraction (pXRD) pattern of a simple crystal structure defined by the user. By using sliders to control the lattice parameters and the angles between the crystallographic axes, the diffraction pattern updates instantly, allowing the user to visualize the effect of each parameter on the pattern in real time. 

The program also allows the inclusion of up to 10 atoms in the unit cell, with full control over their atomic type and positions. It is a useful and intuitive tool for teaching and leasning pXRD concepts! 

Feel free to use it, and we would appreciate it if you cite our work!  :D  

You can download the paper from:
https://journals.iucr.org/j/issues/2025/02/00/dv5023/index.html

Please, help to improove **XRD Playground**! If you find a bug, have any difficulties during installation, or have suggestions for improvements, feel free to contact us. 

---

## Known installation issues

1. **Debian (using Miniforge and conda-forge)**

   There is an issue with a dependency in `xrayutilities` that calls a deprecated SciPy function; reinstalling `xrayutilities` using pip solves the problem: 

   pip install --force reinstall xrayutilities

3. **Windows and Linux (using Anaconda)**

    A similar issue may occur due to a broken dependency in `xrayutilities`. Reinstalling it using `pip` has been reported to fix the problem.
