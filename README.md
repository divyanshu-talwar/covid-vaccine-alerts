# Covid Vaccine Alerts
## Overview
A simple python script to setup email alerting for available vaccine slots for your pincode.

## Execution
* `pip install -r requirements.txt`.
* Update the params in the script `alert_on_availability.py`.
	* A new google account could be created to configure the sender.
	* Please ensure that the access for less secure apps is turned on for the sender's google account.
* Execute the script using `python3 alert_on_availability.py`.