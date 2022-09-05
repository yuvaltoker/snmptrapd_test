# sweet! this thing has just worked so... thanks for reading this, and let's get to the point!

# for building the images and running the containers just type in the terminal:
```bash
docker-compose up
```
# after that two images are suppose to be built, and the two containers are suppose to be up and running. 

# to see the snmptraps messages, you'll need to first get in the container.
# type in the terminal:
```bash
docker exec -it testing_snmptrapd bash
```
# great! now you're in the container where the snmptrap daemon is on. now you'll need to open the file.log.
# type in the terminal:
```bash
nano file.log
```
# the visuallization of the incoming snmptraps is static, which means when you open the file you'll see the current state.

# so in order to see the incoming snmptraps just close the file and open it again.  

