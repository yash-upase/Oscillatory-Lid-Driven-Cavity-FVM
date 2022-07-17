# Oscillatory-Lid-Driven-Cavity-FVM
The MatLab code consists of non-dimensional Navier-Stokes solver written as part of Computaional Fluid Dynamics course.
The discretization is followed from the theory of the sourse.

The Python code consists of the Navier-Stokes solver for Lid Driven Cavity problem in primitive variable form (u,v,p). The code was adapted and modified from the osriginal code by Prof. Saad, the course of whom provides excellent study material for the problem. I dont really know how to credit him on GitHub hence I want to acknowledging his work here.

## Grid Independance Study
Before analysis grid-independance study was performed. This is like doing balancing act between computing power that we can spend and accuracy we seek.

<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Grid%20Independance%20Study.png" width="500" height="500">

## Validation with Ghia's Bechmark results


<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Re%3D100.png" width="500" height="500">
The first top left figure shows velocity stramlines, the second on top right shows vorticity contours. The below two are validation plots (y Vs U_vel and V_vel Vs x)

## Velocity Stramlines

<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/128_128_1000Re.png" width="500" height="500">

The above figure shows the velocity streamline for fully developed flow for Re = 1000. If we increase the Re, then we can observe the secondary vortices developing as well.  

## Single Wall Oscillations

Following are the plots for Single Wall Oscillations with : $\omega = 2\pi/6$

<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Velocity_u_y_at_Re%3D1000_single.png" width="400" height="400"><img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Velocity_x_v_at_Re%3D1000_single.png" width="400" height="400">
<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/osci_1_omega_2_pi_by_6_single120.png" width="400" height="400"><img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Vorticity_at_Re%3D1000_single_120.png" width="400" height="400">

## Double Wall Parallel Oscillations
Following are the plots for Double Wall Parallel Oscillations with : $\omega = 2\pi/6$

<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Velocity_u_y_at_Re%3D1000_parallel.png" width="400" height="400"><img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Velocity_x_v_at_Re%3D1000_parallel.png" width="400" height="400">
<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/osci_1_omega_2_pi_by_6_parallel120%20.png" width="400" height="400"><img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Vorticity_at_Re%3D1000_parallel_120.png" width="400" height="400">

## Double Wall Anti-Parallel Oscillations
Following are the plots for Double Wall Anti-Parallel Oscillations with : $\omega = 2\pi/6$

<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Velocity_u_y_at_Re%3D1000_Anti.png" width="400" height="400"><img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Velocity_x_v_at_Re%3D1000_Anti.png" width="400" height="400">
<img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/osci_1_omega_2_pi_by_6_anti120.png" width="400" height="400"><img src="https://github.com/here-is-yash/Oscillatory-Lid-Driven-Cavity-FVM/blob/main/Result%20Plots/Vorticity_at_Re%3D1000_Anti_120.png" width="400" height="400">
