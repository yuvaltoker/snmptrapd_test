#SNMP traps

In order to build the images and run the containers just type in the terminal:
```bash
docker-compose up
```
Right after that, two images are suppose to be built, and the two containers are suppose to be up and running based on their images. 

Where can i find the trap messages? 
First, get in the container-
type in the terminal:
```bash
docker exec -it testing_snmptrapd bash
```
Great! now you're in the container where the snmptrap daemon is located. next you should open the file.log.
type in the terminal:
```bash
nano file.log
```
The visuallization of the incoming snmptraps is static, which means when you open the file you'll see the current state.

so in order to see the incoming snmptraps just close the file and open it again.  

