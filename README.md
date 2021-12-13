### Lets eat

This is an example from
[fareskalaboud/LearnPDDL](https://github.com/fareskalaboud/LearnPDDL), with some
minor tweaks. A robotic arm needs to move and grab the cupcake in order to eat.

### Delivery Drivers

This is a slighly more complex example, which simulates delivering cargo via
vehicles. Each vehicle has a capacity, which much be greater than (or equal to)
the size of what the vehicle wants to carry. In order to have greater
efficiency, each vehicle has a minimum distance they need to cover to make a
trip. That means that, if the cargo is not far enough from its destination, the
vehicle won't pick it up.

There are two problems related to this domain:

- [different-sizes](https://github.com/NeoVier/PDDLExamples/blob/main/delivery-drivers/different-sizes.pddl)
deals with multiple vehicles that can carry different-sized cargos, and travel
different lengths.
- [different-locations](https://github.com/NeoVier/PDDLExamples/blob/main/delivery-drivers/different-locations.pddl)
deals with multiple locations, simulating an airplane that can go to set
destinations, and needs to deliver cargo around the world.
