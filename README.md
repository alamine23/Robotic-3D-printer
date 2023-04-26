# Robotic-3D-printer
Modeling and simulation of robots for 3D printing applications
Summary: Rapid free-form printing of particle-functionalized materials is an integral component of 3D printing and additive manufacturing. Such processes consist of attaching a dispenser to a robot arm which then releases droplets of specialized mixtures in free-space that are deposited onto a substrate. These approaches are popular because they utilize widely-available, highly-programmable, robots. However, often the release of a complex mixture in free-space is somewhat imprecise, thus electrodynamic field control has been proposed as a possible remedy to enhance the precision of such processes. Specifically, electrodynamic control of the material is achieved by electrifying the released material in the presence of a prescribed ambient electrical field generated from the substrate, in order to guide it to the desired position. There are many components that comprise such a system, thus motivating the construction of a simulation tool framework assembling submodels of the:

• kinematics of the robot arm and the dispenser-printer head,

• electrodynamic and gravitational forces on the released material,

• dynamics of the released material and

• conductive, convective and radiative cooling of the media.

Numerical simulations are undertaken to illustrate the overall system model, which is comprised of an assembly of submodels. Afterwards, a Machine Learning Algorithm (MLA) is developed to identify and optimize the proper system parameters which deliver a desired printed pattern. Specifically, an MLA is
developed to ascertain the appropriate combination of robotic motion and electrical fields needed to create structures which would be difficult or impossible by purely mechanical means alone.

<img width="490" alt="Screenshot 2023-04-25 at 10 49 41 PM" src="https://user-images.githubusercontent.com/124940176/234481297-9b78bfa0-4dfa-4193-83b8-145bfe6b63a5.png">
