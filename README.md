# Bluetooth quick connect

Quickly connect and disconnect from the bluetooth devices you use the most.

![bt_menu](https://user-images.githubusercontent.com/42439472/164915659-777e0c2e-bb73-4a45-9ae7-63ab21f1808e.png)

This extension is listed on the Ulauncher extensions page. https://ext.ulauncher.io/-/github-eckhoff42-ulauncher-bluetooth-quick-connect

## Settings
![settings](https://user-images.githubusercontent.com/42439472/164915725-84710383-3d91-47ad-80ed-8a3b20b98bf2.png)


Change the keyword in under *Bluetooth manager Keyword*

Add your devices in the *Device list*. The format is as follows:
```python
headset A1:A2:17:6E:87:C1, Keyboard A1:A2:90:19:04:2D
```
You can find your devices mac address in the bluetooth settings or with the command `bluetoothctl scan on`

**N.B.** this extension uses `bluetoothctl` to connect to your devices. 
Find information about downloading it here: https://command-not-found.com/bluetoothctl
