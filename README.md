# Stealthwatch Sample Scripts
This repository contains sample Python scripts and Postman collections related to Cisco Stealthwatch Enterprise. It is available for use by the Cisco DevNet community through Code Exchange.
For more information on the Stealthwatch Enterprise REST API, please see the following link: https://developer.cisco.com/docs/stealthwatch
<br/><br/>
This project is split into 2 sections: 
* [Python samples](./python-samples)
* [Postman samples](./postman-samples)

## Compatibility
A minimum Stealthwatch Enterprise version of 6.10.0 is required to use these sample scripts (with the exception of the `Get Flows` REST API capability which requires minimum Stealthwatch version 7.0.0).

## Python samples
#### Installation
1. Ensure Python 3 is installed.
   * To download and install Python 3, please visit https://www.python.org.
2. Ensure the Python `requests` module is installed.
   * For more information on the Python `requests` module, please visit https://pypi.org/project/requests/.
3. Download the `.py` files located in the [python-samples](./python-samples) directory.

*Alternatively, advanced users can also use git to checkout / clone this project.*

#### Configuration
Open the desired `.py` file that you intend to run and enter the following values where specified:
* `SMC_USER = ""`
* `SMC_PASSWORD = ""`
* `SMC_HOST = ""`

*(Note: additional fields may also be required)*

#### Usage
<!--
Show users how to use the code. Be specific. Use appropriate formatting when showing code snippets or command line output. If a particular [DevNet Sandbox](https://developer.cisco.com/sandbox/) or [Learning Lab](https://developer.cisco.com/learning-labs/) can be used in to provide a network or other resources to be used with this code, call that out here.
-->
1. Identify the path to your Python 3 executible. 
    * Depending how Python 3 was installed, this might be as simple as just calling the command `python` or `python3`.
2. Run the Python script with the following command:
    * `$ <PYTHON-PATH> <PYTHON-SCRIPT-PATH>`
    * Example: `$ /usr/bin/python ./get_flows.py`

## Postman samples
#### Installation
1. Ensure Postman is installed.
   * To download and install Postman, please visit https://www.getpostman.com.
2. Download the Postman collections and environment files located in the [postman-samples](./postman-samples) directory.
3. After launching Postman, click the `import` button and import the previously downloaded Postman files.

#### Configuration
1. Ensure the Postman collections and environment have been imported.
2. Select the `Stealthwatch Enterprise - DevNet` environment from the dropdown in the top-right corner of Postman.
3. To the right of this dropdown (in the top-right corner of Postman), click the graphic of the gear to edit the Postman environment.
4. Please set the following fields appropriately:
    * `STEALTHWATCH-SMC`
    * `username`
    * `password`

#### Usage
1. From the Collections list on the left side of Postman, select the desired collection as well as the desired request to run.
2. If necessary, modify any parameters in either the `params` section or the `body` section of the request.
3. When ready, press the `send` button to run the Postman request, and view the response below. 

*For more information on how to use Postman, please visit https://learning.getpostman.com.*

## Known issues
No known issues.

## Getting help
Use this project at your own risk (support not provided). If you need technical support with Cisco Stealthwatch APIs, do one of the following:

##### Browse the Forum
<!--
Check out our forum to pose a question or to see if any questions have already been answered by our community. We monitor these forums on a best effort basis and will periodically post answers. 
-->
*Coming soon...*

##### Open A Case
* To open a case by web: http://www.cisco.com/c/en/us/support/index.html
* To open a case by email: tac@cisco.com
* For phone support: 1-800-553-2447 (U.S.)
* For worldwide support numbers: www.cisco.com/en/US/partner/support/tsd_cisco_worldwide_contacts.html

## Getting involved
Contributions to this code are welcome and appreciated. See [CONTRIBUTING](./CONTRIBUTING.md) for details. Please adhere to our [Code of Conduct](./CODE_OF_CONDUCT.md) at all times.

## Licensing info
This code is licensed under the BSD 3-Clause License. See [LICENSE](./LICENSE) for details. 

