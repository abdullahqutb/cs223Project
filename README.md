Bilkent University - CS223 (Digital Design) - Fall 2018

CS223, Digital Design, Lab project.

CS223 Laboratory Project
Smart Evacuation Elevator

Description:
Nowadays, in parallel with the increasing workload of modern life and increasing pace of daily life, more efficient functionality is expected from elevator systems. In the evaluation of the efficiency of an elevator control system, the elevator distribution method, which determines which elevators to be assigned to the incoming calls, plays a critical role. The elevator distribution method used must provide solutions to some exceptional cases like evacuation scenarios (this is a special elevator which can be used for evacuation). Expectations of passengers are waiting time, movement time and travel time as short as possible. Therefore, in terms of targeted requirement, an elevator distribution method deals with the minimization of these parameters. On the system side, it is desirable to optimize the number of passengers that can be serviced at the same time, the movement time of the elevators and the number of stops.
Reset State: Regardless of the state of the elevator, elevator will be located at Floor 0 and it will be empty.
Each stop of elevator at a floor will take 2 seconds.
Travel time of elevator between adjacent floors will take 3 seconds.
Maximum number of passengers waiting for an elevator at a floor is limited by 12.
On each press of (Passenger+) button the number of passengers waiting at that floor will increase by one and each elevator waiting passengers will be shown by a single red LED at the same floor.
