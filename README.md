# ESP HTTP Request example
This project demonstrates how to use a GET request with the esp32 Wifi driver and can be further used for all other types if REST API.

## Running the Project:

Before building the project, be sure to follow the [ESP-IDF Getting Started Guide](https://idf.espressif.com/) to ensure you have the required development environment.

To build the project project:

* Change into the directory of project file you'd like to build.
* Run `idf.py set-target TARGET` to select the correct chip target to build before opening the project configuration menu. By default the target is `esp32`. For all options see `idf.py set-target --help`
* Run `idf.py menuconfig` to open the project configuration menu. Most examples have a project-specific "Example Configuration" section here (for example, to set the WiFi SSID & password to use).
* `idf.py build` to build the project.
* Run `ls /dev/tty*` to view the PORT the microcontroller is connected to.
* Run `idf.py -p PORT flash`to flash the code into the microcontroller.
* Run `idf.py monitor` to run ESP-IDF monitor to view logs and print statements.
