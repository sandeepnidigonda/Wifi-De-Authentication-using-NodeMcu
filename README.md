# Wifi-De-authentication-using-NodeMcu

Deauthentication Attack Logic:
1.Identification of Target: The attacker first identifies the Wi-Fi network they want to target and the devices connected to that network. This information can often be gathered by scanning the surrounding wireless networks and their associated devices.
 
2.Capture MAC Addresses: The attacker collects the MAC (Media Access Control) addresses of the devices currently connected to the target Wi-Fi network. MAC addresses are unique identifiers assigned to each network interface on a device.
 
3.Craft Deauthentication Frames: Using a tool or script, the attacker crafts deauthentication frames or disassociation frames. These frames contain the MAC addresses of the targeted devices and are designed to mimic legitimate network management frames.
 
4.Send Deauthentication Frames: The attacker then broadcasts these deauthentication frames within the vicinity of the target network. It's important to note that the attacker does not need to be connected to the network themselves; they only need to be within range.
 
5.Disruption: When the target devices receive these deauthentication frames, they interpret them as a signal to disconnect from the Wi-Fi network. This disruption causes the devices to lose their network connection temporarily!
6.Reconnection: After being disconnected, the targeted devices will automatically attempt to reconnect to the Wi-Fi network. During this process, legitimate users may experience a delay or interruption in their network access.
 
7.Repeat: The attacker can continue sending deauthentication frames periodically to keep the disruption ongoing, making it challenging for legitimate users to maintain a stable network connection![image]
What is the ESP8266 (Node MCU)?

The ESP8266 is a low-cost Wi-Fi-enabled microcontroller chip that has gained popularity in recent years due to its versatility and compatibility with the Arduino platform!
