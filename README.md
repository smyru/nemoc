# nemoc
This is Nemo Command line controller for Sailfish OS phone connecting to the device over SSH.

If your Jolla has SSH enabled and is connected to a network, thanks to nemoc you will be able to use the phone from a terminal on your laptop or desktop.

### EXAMPLES
To lock your phone from computer terminal just issue:

    $ nemoc lock

To mute the phone:

    $ nemoc mute

To unmute:

    $ nemoc mute off

To call a number:

    $ nemoc call +123456789

To send an sms:

    $ nemoc sms +123456789 "Hi, could you call me in the evening?"

To switch Bluetooth state:

    $ nemoc bluetooth on
    $ nemoc bluetooth off

For more usage examples issue: `nemoc -h`
