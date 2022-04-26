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
