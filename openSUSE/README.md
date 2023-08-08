# mySystemHealth openSUSE

This script will update your system by refreshing the package list, downloading and installing any available updates, and removing any outdated packages and configuration files.

# Tumbleweed

## Usage

1. Download the file.  

2. Make it executable with the command.

```
chmod +x mysystemhealth
```

3. You can run it using the command

```
sudo ./mysystemhealth <parameter>
```

### Parameters
```
-h          display this help and exit   

-r          After completing all the tasks, reboot the system   

-s          After completing all the tasks, shutdown the system
```

## Use as root user.

You better copy the file in your **/usr/bin** folder.

```
sudo cp mysystemhealth /usr/bin/
```

Then you can run the command on your terminal usind the following command.

```
sudo mysystemhealth <parameter>
```

# Leap

## Usage

1. Download the file.  

2. Make it executable with the command.

```
chmod +x myleapsystemhealth
```

3. You can run it using the command

```
sudo ./myleapsystemhealth <parameter>
```

### Parameters
```
-h          display this help and exit   

-r          After completing all the tasks, reboot the system   

-s          After completing all the tasks, shutdown the system
```

## Use as root user.

You better copy the file in your **/usr/bin** folder.

```
sudo cp myleapsystemhealth /usr/bin/
```

Then you can run the command on your terminal usind the following command.

```
sudo myleapsystemhealth <parameter>
```
