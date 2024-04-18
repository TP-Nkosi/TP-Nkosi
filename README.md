
# SDN OpenFlow Firewall

This project implements a firewall using a Software Defined Networking (SDN) platform called Pyretic. The firewall rules are provided in a configuration file `firewall-config.pol`, allowing for easy modification without altering the switch code.

## Installation

1. Clone the repository:

   git clone https://github.com/TP-Nkosi/SDN-OpenFlow-firewall.git

2.Install Pyretic and its dependencies. Refer to the Pyretic documentation for installation instructions.

3.Place your firewall rules in the firewall-config.pol file. Follow the syntax and guidelines provided in the sample configuration file.

Usage
    1. Ensure your SDN controller is running and reachable by the Pyretic application.
    2. Start the Pyretic application with the firewall rules:
pyretic.py pyretic.modules.firewall.firewall -m p0 pyretic/modules/firewall/firewall-config.pol

3.Monitor the firewall behavior and verify that it's enforcing the configured rules.

Configuration

Modify the firewall-config.pol file to adjust the firewall rules according to your network security requirements. Refer to the Pyretic documentation for guidance on writing firewall policies.
Contributions

Contributions to this project are welcome! Feel free to fork the repository, make changes, and submit pull requests.
Issues

If you encounter any issues or have suggestions for improvements, please open an issue on GitHub.

License

This project is licensed under the MIT License.


You can use this README.md file to provide an overview of your project, installation instructions, usage guidelines, configuration details, information about contributions and issues, and the project's license.