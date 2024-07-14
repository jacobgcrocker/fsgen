# fsgen
Flight Simulator Lightweight Charter Airline Manager


Ideas: 

Config.yaml file to input: 
    Charter Airline Name
    Pilot Name
    List of serviced airports
    VIP client list

Fleet.yaml file to input: 
    Aircraft fleet: 
    - registration
    - icao type
    - passenger count, max weight
    - runway type (future plan)
        /s solid
        /w water
        /g gravel
    - aircraft location (icao)


Primary Function: 
    Generate a flight with the following parameters: (*required)
    - origin*
    - destination
    - aircraft*
    - VIP(s)
    After flight generation, prompt user to enter when flight is complete
    - if not, prompt for ICAO of diversion, or if returned to origin.

Future Potential Features:
    - User Interface
    - Simbrief Export
    - Airport Data import
    - Aircraft data import
    - Revenues and Costs (economy management)
