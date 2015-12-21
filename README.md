# MikroTik Winbox Linux packaging

Create MikroTik Winbox packages.

## Requirements

* curl
* ruby + gem + fpm (```gem install fpm```, this needs package ```ruby-dev```)

## Usage

Just run the create script like  ```./create``` and it downloads the _winbox.exe_ file and create a deb package. As fpm is able to build other packages too, you might adjust ```-t deb``` in function ```create_deb``` with another type e.g. _rpm_.
