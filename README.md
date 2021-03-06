# Remote Code Execution Framework
Term project for CMPE273 Fall 21

## 1. Architecture diagram
![image](https://user-images.githubusercontent.com/18122083/144533602-04c49787-197c-4759-90d8-e8ca2285d167.png)


## 2. Job Distribution

We have made the load balancing algorithms configurable! 

### Cache Design
![image](https://user-images.githubusercontent.com/18122083/144533571-ea9ce97d-79f5-43fe-806a-98bf42ebe0ba.png)

Algorithms:
### 1. Least recently used
Allocates the job to the lease recently used node


### 2. Random allocation
Randomly allocates the job to any of the available nodes

### 3. Time modulus
Based on the timestamp of the request, jobs are routed to any of the available nodes


## 3. Auto Scaling
![Screenshot 2021-12-02 at 5 33 54 PM](https://user-images.githubusercontent.com/51155654/144533282-b06dd749-7de2-4589-a3d0-d120aac0e3db.png)



## 4. Worker implementation


## 5. Client Implementation and Demo

### Health Statistics
![image](https://user-images.githubusercontent.com/18122083/144533030-d15147b6-66c3-4d79-8c4e-a9423ef4595a.png)

### Code output
![image](https://user-images.githubusercontent.com/18122083/144533109-f5191c41-2199-41a1-9b57-a3f5836bb2d1.png)



https://github.com/1919kiran/cmpe273-fall21-team7-project/issues/1#issue-1070141969
