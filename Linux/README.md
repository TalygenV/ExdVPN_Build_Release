
### Install the `.deb` File

Run the following command to install the package:

```bash
sudo dpkg -i /mnt/data/exdvpn.deb
```

After successful installation, run the following command to start the VpnClient:

```bash
sudo vpnclient start
```

It will show the following message on the screen:

```bash
The ExdVPN Client service has been started.
```

Now run `vpncmd` to configure the VPN client:

```bash
sudo vpncmd
```

It will show the following output:

```plaintext
vpncmd command - ExdVPN Command Line Management Utility 
By using vpncmd program, the following can be achieved. 

1. Management of VPN Server or VPN Bridge 
2. Management of VPN Client
3. Use of VPN Tools (certificate creation and Network Traffic Speed Test Tool)

Select 1, 2 or 3:
```

Now press **2** to configure the VPN client.
