- Overview of real-time scheduling algorithms:
1. Clock driven
2. Weighted round robin
3. Priority driven :
        - Dynamic vs static
        - Deadline scheduling : EDF and LST
- Outline relative strengths, weaknesses.

## Task states
![image](https://user-images.githubusercontent.com/80462415/168714167-8d1e182a-6298-4eb6-802a-3e76d8f5277e.png)
## Feasible schedule
- A  schedule that never misses any deadline called **Feasible**
- A set of task is _**schedulable**_ if there exists at least a feasible schedule
- Optimal scheduling algorithm always produces a feasible shedule in case a given set of tasks is schedulable
![image](https://user-images.githubusercontent.com/80462415/168714835-f4a473c6-ddef-4038-8634-153c6ba0b0a1.png)

## Approaches to Real-time scheduling
![image](https://user-images.githubusercontent.com/80462415/168716731-7cfaa736-f422-4d03-ae39-af84e8e0a497.png)
## Weighted round-robin
![image](https://user-images.githubusercontent.com/80462415/168716758-14d20ac5-9413-4a79-a392-88f41dc902a2.png)
### Weighted round-robin overview:
![image](https://user-images.githubusercontent.com/80462415/168716987-18e127dd-acc8-413b-9ef5-05333985bf47.png)
### Weighted round-robin example:
![image](https://user-images.githubusercontent.com/80462415/168717959-37a71fcf-cee8-4ebb-965d-b9d42c976f6d.png)


## Clock-driven Scheduling 
- Scheudling decision time :  point in time when scheduler decides which job to execute next
- SDT in clock-driven schedulers is defined a prori before the system begins execution
![image](https://user-images.githubusercontent.com/80462415/168718084-dd29252c-63a8-4f02-8b15-b474e7435da7.png)
## Prority Scheduling : 
### Overview
- **Basic rule**:  never leave processor idle when there is work to be done:

  + Work conserving scheduling
  + Greedy scheduling
  + List scheduling
- Possible implementation of preemptive prority-driven scheduling:
  + Assing priorities to jobs
  + Scheduling decisiong are made when: 
  ![image](https://user-images.githubusercontent.com/80462415/168718265-ae52112a-4de8-41d1-a1eb-4c89de0be1a4.png)
  + At each scheduling decision time, choose ready task with highest priority
- In non-preemptive cases, scheduling decisions are made only when processor becomes idle
### Scheduling decision point
![image](https://user-images.githubusercontent.com/80462415/168719029-cd4de0d3-81e6-4b41-8a76-a40d18a6106a.png)
### Example
![image](https://user-images.githubusercontent.com/80462415/168719056-bc3e4145-7cb3-4940-8340-e5e7f300946d.png)
