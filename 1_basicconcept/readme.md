> source 🌐 : https://bitly.com.vn/45bdjg
## Intent 
1. Systems process data at a regular timely rate : - Aircraft positioning system
2. Systems rapid response to irregular events: - Over - temperature failure in a nuclear plant
## System concept
![image](https://user-images.githubusercontent.com/80462415/165207933-cc5e971f-8a51-4f96-8309-714f6d39ec85.png)
## Real-time systems
- Typical real-time control system:
    + input: sensors + imgage device : analog => digital
    + outputs: control signals + display : digial => analog


![image](https://user-images.githubusercontent.com/80462415/165208668-3cf58985-2ba7-4833-ab0d-bcfff63a607d.png)

- A classic representation of a real-time system
    + sequence of jobs to be scheduled
    + hidden hardware complexity


![image](https://user-images.githubusercontent.com/80462415/165208722-75512271-8061-456f-a331-3be6d99621c6.png)

> A real-time system is a system that **must satisfy** explicit response=time constraints or risk severe consequences including failure
- failure : inability of the system to perform according to system specification


- Reactive system: 
    + scheduling is driven by ongoing interaction with their evnironment : fire-control system
    
    ![image](https://user-images.githubusercontent.com/80462415/165209325-a08223d1-1946-4c37-b67d-eccc17e3d559.png)


- Embedded systems:
    + inside a system (not itself a computer)
    + e.g: embedded computers in an automobile: fuel injection, airbag deployment...

![image](https://user-images.githubusercontent.com/80462415/165209487-f853aabf-5ecb-47de-802e-cfa99efe42b1.png)

- Block diagram of a generic real-time control system:


![image](https://user-images.githubusercontent.com/80462415/165210132-7f304b03-5475-4aeb-a7c2-0a742d793e9c.png)

# When is a system - realtime
![image](https://user-images.githubusercontent.com/80462415/165211008-dce209f7-0a22-4ebd-9311-da06e4950466.png)

# Soft vs Hard
> A **soft** real-time system is one in which performance is degraded but not desotryed by failure to meet response-time constraint
> A **hard** real-time system is one in which failure to meet a **single deadline** may lead to complete and castatrophic system failure

![image](https://user-images.githubusercontent.com/80462415/165211231-eb883d99-7a49-4bc6-b12c-2f0310ceb0bc.png)

- Example: ❔ Which systems can be considered as hard or soft real-time systems ? Why?
> Automated teller machine
> Embedded navigation controller for autonomous robot weeb killer
> Avionics weapons delivery system in which pressing a button launches an air-to-air missile


> A **firm** real-system is the one which could missed a few deadlines then would not lead to total failure, but missing more than a few may lead to complete and castastrophic system failure
# Where do the deadlines come from
- Underlying physical status of the system under control
        + Images updated at approximately 30 frames/second
        + Accelerations ,must be read at a rate based on the velocity of the vehicle
