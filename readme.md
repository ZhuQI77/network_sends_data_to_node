# Let's create 4 device-profiles, which are class A otaa, class C otaa, class A abp, class C abp.

##	The configuration of class A otaa is as follows

![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_A_otaa_01.png)
****
![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_A_otaa_02.png)

##	The configuration of class C otaa is as follows

![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_C_otaa_01.png)
****
![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_C_otaa_02.png)
****
![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_C_otaa_03.png)

##	The configuration of class A abp is as follows

![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_A_abp_01.png)

##	The configuration of class C abp is as follows

![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_C_abp_01.png)
****
![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/class_C_abp_02.png)

# Create 4 devices, each device corresponds to a device-profile. When creating an abp device, you must check "Disable frame counter validation".

![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/four_device.png)
****
![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/abp_device.png)

# In otaa mode or abp mode, the network server can actively send data to the node only after the network server successfully receives a piece of data from the node.

# In class C mode, the node will immediately receive the data sent by the network server.

# But in class A mode, the node will not immediately receive the data from the network server. The node needs to send a piece of data to the network server before the node can receive the data from the network server.

![image](https://github.com/ZhuQI77/network_sends_data_to_node/image/downlink.png)

