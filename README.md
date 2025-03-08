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
```bash
AJ-Drone/
│
├── code/
│   ├── firmware/                     # Drone firmware
│   ├── software_interface/           # Interface logic between drone and software
│
├── docs/
│   ├── overview.md
│   ├── modules/                      # Documentation on individual modules
│
├── include/
│   ├── flightControl.h
│   ├── communication.h
│
├── src/
│   ├── modules/
│   │   ├── flightControl/
│   │   │   ├── flightControl.cpp
│   │   │   ├── flightControl.h
│   │   ├── communication/
│   │   │   ├── communicationHandler.cpp
│   │   │   ├── communicationHandler.h
│   │   ├── sensors/
│   │   │   ├── sensorManager.cpp
│   │   │   ├── sensorManager.h
│   ├── networking/
│   │   ├── networkCommunication.cpp
│   │   ├── networkCommunication.h
│   ├── scripts/
│   ├── tests/
│   │   ├── modules/
│   │   │   ├── flightControl_tests.cpp
│   │   │   ├── communication_tests.cpp
│   ├── config/
│   │   ├── flight_params.yaml
│   │   ├── network_settings.json
│
├── schematics/
│   ├── designs/
│   ├── circuits/
```
