Virtual Machine for IoT Exercises
---------------------------------

1. Install VirtualBox via https://www.virtualbox.org/wiki/Downloads

2. Import iot_vm.ova and start the VM
	*Requirements: at least 2GB RAM, and 16 GB HDD
	
	Host:     iotvm
	Username: dev
	User:     IoT Developer
	Password: iotdeveloper


3. Run Softwares
----------------

a. Node-RED

	i) Launch: System Tools -> LXTerminal

		TYPE: node-red
			AND ...
		      Ctrl-C to stop

	ii) Launch Firefox browser and visit: http://127.0.0.1:1880/


b. Fritzing
	
	i) Launch: System Tools -> LXTerminal

		TYPE: /opt/fritzing/Fritzing

c. IntelliJ

	i) Launch: System Tools -> LXTerminal

		TYPE: /opt/ideaIC/bin/idea.sh


d. CouchDB

	i) Launch: System Tools -> LXTerminal

		TYPE: sudo service couchdb start
			AND ...
		      sudo service couchdb stop

	ii) Launch Firefox browser and visit: http://127.0.0.1:5984/_utils/


f. ArangoDB

	i) Launch: System Tools -> LXTerminal

		TYPE: sudo service arangodb3 start
			AND ...
		      sudo service arangodb3 stop

	ii) Launch Firefox browser and visit: http://127.0.0.1:8529/


e. InfluxDB

	i) Launch: System Tools -> LXTerminal

		TYPE: /opt/influxdb/influxd
			AND ...
		      Ctrl-C to stop

	ii) Launch Firefox browser and visit: http://127.0.0.1:8086/


g) MPLab X IDE (v5)
	
	i) Launch: Programming -> MPLAB IDE


