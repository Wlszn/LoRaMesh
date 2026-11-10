This folder will hold the scripts we use to set up and test our MeshCore devices.

## What will go here

- **`repeater/configure_repeater.py`**: This file will connect to a repeater over the USB port and send its setup commands, so every repeater is configured the same way when we buy our heltech devices.

- **`repeater/capture_status.py`**: This file will run on a device and capture and save the outputs it receives in the evidence folder

All other scripts that we need will go into this folder that way all teammates have access to it and can use them when needed.