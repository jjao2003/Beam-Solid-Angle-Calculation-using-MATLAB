# Beam Solid Angle Calculation using MATLAB

## Author
Agozie Onuigbo  
Savonia University of Applied Sciences  

## Objective
To compute the Beam Solid Angle (ΩA) of an antenna using MATLAB numerical integration.

---

## Theory

The beam solid angle is defined as:

ΩA = ∫∫ F_n(θ,φ) sinθ dθ dφ

If independent of φ:

ΩA = 2π ∫ F_n(θ) sinθ dθ

Directivity:

D = 4π / ΩA

---

## MATLAB Implementation

The program:

- Defines θ from 0 to π
- Defines normalized radiation pattern F_n(θ)
- Computes numerical integration using trapz()
- Calculates directivity
- Plots radiation pattern

---

## Results

Beam Solid Angle ≈ 2.0944 steradians  
Directivity ≈ 6

---

## How to Run

1. Open MATLAB
2. Run Beam_Solid_Angle.m
3. View command window output and plots

---

## Conclusion

The experiment demonstrates numerical computation of beam solid angle using MATLAB integration methods.
