# MqttClient_Client_for_AWS_IoTCore
Mqtt Client for AWS IoTCore using "asyncio"

step 1 : Unzip contents
step2 : run the bash/ AWS_IoT_CreateThing_RegisterCertificates.sh shell script to create a new IoT thing (use proper names) and create + assign keys and certificates
step3 : store the correct certificates generated from step2 into the folder in zip file = certificates/
step4 : edit config.py to add in the correct Endpoints and certificate paths
step5 : Run IoT_Device_ops.py for pub_sub operations
