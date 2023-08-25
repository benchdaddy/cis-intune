# CIS Intune Benchmarking

This allows you to import 99% of the Intune benchmark recommendations from CIS to your Intune Configuration Policy menu. Currently, CIS do not provide anything to help save time and resources.

I highly recommend you audit the Image you want to harden first and edit the JSON file as required to align with your requirements. This JSON file by default has the L2 options too.

## Installation

Navigate to Graph Explorer and authenticate
Create a POST request: POST https://graph.microsoft.com/v1.0/deviceManagement/deviceConfigurations
Copy the JSON  and paste it in the request body
(Optional) modify the name value if required

## Disclaimer

Please use this as you will but I don't take any responsibility for any issues caused by using import.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
