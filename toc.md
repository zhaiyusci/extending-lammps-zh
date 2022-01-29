- [ ] Foreword
- [ ] Contributors
- [ ] Preface

Section 1: Getting Started with LAMMPS

1 MD Theory and Simulation Practices

- [ ] Technical requirements
- [ ] Introducing MD theory
- [ ] Understanding the dynamics of point particles
- [ ] Performing iterative updates using the Velocity Verlet algorithm
- [ ] Understanding rotational motion
- [ ] Examining temperature and velocity distribution of particles
- [ ] Implementing MD simulation practices
- [ ] Summary
- [ ] Questions

2 LAMMPS Syntax and Source Code Hierarchy

- [ ] Technical requirements
- [ ] Introducing the LAMMPS input script structure
- [ ] Introducing the source code repository
- [ ] Reviewing the source code hierarchy
- [ ] Summary
- [ ] Further reading
- [ ] Questions

Section 2: Understanding the Source Code Structure

3 Source Code Structure and Stages of Execution

- [ ] Technical requirements
- [ ] Introducing parent and child classes
- [ ] Stages of executing the simulation
- [ ] Role of pointers class
- [ ] Parsing input script commands by input.cpp
- [ ] Summary
- [ ] Further reading
- [ ] Questions

4 Accessing Information by Variables, Arrays, and Methods

- [ ] Technical requirements
- [ ] Accessing atom properties during simulation runs
- [ ] Requesting a neighbor list
- [ ] Accessing physical constants
- [ ] Reading parameters from the input script
- [ ] Incorporating new data types
- [ ] Summary
- [ ] Questions

5 Understanding Pair Styles

- [ ] Technical requirements
- [ ] Reviewing the general structure of pair styles
- [ ] Reviewing the Morse potential
- [ ] Reviewing the table potential
- [ ] Reviewing the DPD potential 80 Questions
- [ ] Summary
- [ ] Questions

6 Understanding Computes

- [ ] Technical requirements
- [ ] Reviewing the general structure of computes
- [ ] Reviewing the compute KE class
- [ ] Reviewing the compute group/group class
- [ ] Reviewing the compute RDF class
- [ ] Reviewing the compute heat flux class
- [ ] Summary
- [ ] Questions

7 Understanding Fixes

- [ ] Technical requirements
- [ ] Exploring the general structure of fixes
- [ ] Reviewing the Fix AddForce class
- [ ] Studying the Fix NVE class
- [ ] Studying the Fix NH class
- [ ] Studying the Fix Print class
- [ ] Reviewing the Fix Orient/FCC class
- [ ] Analyzing the Fix Wall and Fix Wall/LJ126 classes
- [ ] Exploring the Fix Rigid class
- [ ] Summary
- [ ] Questions

8 Exploring Supporting Classes

- [ ] Technical requirements
- [ ] Discovering the Group class
- [ ] Exploring the Variable class
- [ ] Studying the Error class
- [ ] Reviewing the Memory class
- [ ] Discussing the Angle and angle/harmonic classes
- [ ] Summary
- [ ] Questions

Section 3: Modifying the Source Code

9 Modifying Pair Potentials

- [ ] Technical requirements
- [ ] Writing a harmonic potential
- [ ] Writing a height-dependent pair potential
- [ ] Writing a friction-based pair style
- [ ] Summary
- [ ] Questions

10 Modifying Force Applications

- [ ] Technical requirements
- [ ] Writing a fix to apply a 2D spring force
- [ ] Writing a fix to apply an active force
- [ ] Writing a fix to apply a custom wall force
- [ ] Writing a fix to apply a bond-boost potential
- [ ] Summary
- [ ] Questions

11 Modifying Thermostats

- [ ] Technical requirements
- [ ] Writing a fix to apply the Andersen thermostat
- [ ] Writing a fix to apply a nonlinear temperature increment
- [ ] Writing a fix to print output at evaporation
- [ ] Summary
- [ ] Questions

Appendix A Building LAMMPS with CMake

- [ ] Technical requirements
- [ ] Prerequisites for working with LAMMPS
- [ ] Building LAMMPS
- [ ] Compiling LAMMPS in Windows
- [ ] Developing LAMMPS
- [ ] Building with Make
- [ ] Further reading

Appendix B Debugging Programs

- [ ] Technical requirements
- [ ] What is debugging?
- [ ] Prerequisites
- [ ] Method 1 – Debugging with GDB
- [ ] Method 2 – Debugging with VSCode
- [ ] Insight into sbmask()
- [ ] Further reading

Appendix C Getting Familiar with MPI

- [ ] Technical requirements
- [ ] What is MPI?
- [ ] MPI message
- [ ] MPI in LAMMPS
- [ ] Example of evaluating pi
- [ ] Data exchange between owned atoms and ghost atoms

Appendix D Compatibility with Version 29Oct20

- [ ] Technical requirements
- [ ] Translating Fix Widom into the 3Mar20 version

- [ ] Assessments

- [ ] Index
