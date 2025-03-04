# AJ-Drone

As of right now, the project is still under the drone design process. The processes is as follows:

1. Drone design
2. Modules needed to be design
3. Design schmatics of the modules in LTspice
4. Order modules through manufacturers
5. Program modules
6. 3D print drone design
7. Testing

# Main Goal
The main goal is to produce these drone to students or anyone interested in learning about programming and technology.


# File Structure
(The file structure might change overtime.)

AJ-Drone/ │ ├── code/ # Drone-specific code and firmware │ ├── firmware/ # Main firmware for the drone │ ├── software_interface/ # Interface logic between drone and software │ ├── docs/ # Documentation for the project │ ├── overview.md # Project overview │ ├── modules/ # Module-specific documentation │ ├── include/ # Header files for the modules │ ├── flightControl.h │ ├── communication.h │ ├── src/ # Main source code │ ├── modules/ # Drone functional modules │ │ ├── flightControl/ # Flight control logic │ │ │ ├── flightControl.cpp │ │ │ ├── flightControl.h │ │ ├── communication/ # Communication module │ │ │ ├── communicationHandler.cpp │ │ │ ├── communicationHandler.h │ │ ├── sensors/ # Sensor data management │ │ │ ├── sensorManager.cpp │ │ │ ├── sensorManager.h │ ├── networking/ # Networking code for drone communication │ │ ├── networkCommunication.cpp │ │ ├── networkCommunication.h │ ├── scripts/ # Scripts for testing and automation │ ├── tests/ # Unit tests for the modules │ │ ├── modules/ # Module-level tests │ │ │ ├── flightControl_tests.cpp │ │ │ ├── communication_tests.cpp │ ├── config/ # Configuration files │ │ ├── flight_params.yaml │ │ ├── network_settings.json │ ├── schematics/ # Hardware design and circuit files │ ├── designs/ # PCB and hardware designs │ ├── circuits/ # Circuit diagrams
