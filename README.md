# Drag Force Measurement for External Flow Over Objects

This project presents an experimental study to measure the drag force exerted on a circular cylinder in a wind tunnel setup. Velocity profiles around the cylinder are established to calculate drag force and coefficient, contributing insights for fluid dynamics applications involving cylindrical structures.

## Objectives

- Characterize the drag force on a circular cylinder surface in airflow.
- Establish velocity profile around the cylinder using pitot tube measurements.
- Calculate drag force and drag coefficient based on velocity distribution.
- Compare experimental drag coefficients with literature values and analyze deviations.
- Understand flow characteristics and mass conservation influences on drag.

## Theoretical Background

- Utilized control volume analysis around the cylinder with asymmetrical boundaries to accommodate mass flow differences.
- Drag force derived using momentum equations integrated over velocity profiles.
- Numerical integration performed with the trapezoidal rule to evaluate velocity-dependent integrals.
- Calculation of drag coefficient \( C_D \) using measured drag force and free stream velocity.

## Experimental Setup

- Wind tunnel with test section equipped with holes for pitot tube insertion.
- Pitot tube to measure velocity and pressure differences at multiple heights.
- Micro-manometer to quantify pressure differences.
- Height gauge to accurately position pitot tube for measurements.
- Cylindrical test object placed within test section to simulate external flow over a cylinder.

## Experimental Procedure

- Incrementally measure velocity profiles by moving pitot tube in 2 mm steps along test section height.
- Collect pressure differential data converted to velocity using Bernoulli’s equation.
- Assume symmetric velocity profile about cylinder axis except near boundaries.
- Ignore boundary regions to minimize measurement errors.

## Results

- Velocity profiles plotted using measured data.
- Drag force \( F_D \) and drag coefficient \( C_D \) calculated at various flow speeds.
- Observed \( C_D \) values around 0.9 for flow transitioning from laminar to turbulent, close to literature turbulent values (~0.3) at higher Reynolds numbers (~35000).
- Discrepancies attributed to flow regime transition, setup attachment gaps, and 2D vs 3D experimental differences.

## Errors and Limitations

- Flow regime neither fully laminar nor fully turbulent, affecting drag coefficient comparability.
- Imperfect setup attachment causing flow disturbances.
- Velocity measurement fluctuations and backward flow potential introducing uncertainties.
- Mass conservation assumption challenged by observed disparity between inlet and outlet mass flow rates.

## Conclusion

The drag force measurement experiment highlights challenges in matching theoretical assumptions with experimental conditions, especially mass conservation in control volume and flow regime transitions. Nonetheless, results align reasonably with literature and provide a foundation for further fluid dynamic investigations.

## Acknowledgments

Thanks to Prof. Udipta Ghosh and Prof. Dilip Srinivas Sundaram for guidance and support. Appreciation extended to TAs Gourab Chakraborty and Inzamam Ahmad, and the machine shop staff for technical assistance.

## References

1. Philip J. Pritchard, *Fox and McDonald's Introduction to Fluid Mechanics*, 2011.  
2. Yunus A. Cengel, John M. Cimbala, *Fluid Mechanics*, 2004.  
3. Engineering Purdue AAE520 - Kay-Chibana Wake Report  
4. SV.20file.org Publications  

---

Prepared by Chandra Shekhar, Rupak Banerjee, Piyush Singh, Sridhar Singh, Shaury Kumar Patel  
Mechanical Engineering Department, IIT Gandhinagar  
