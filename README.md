# Citrix NetScaler ADC Zabbix Template 🚀

![GitHub Release](https://img.shields.io/github/v/release/jjsjshi/Citrix_NetScaler_ADC_Zabbix_Template?style=flat-square) ![GitHub All Releases](https://img.shields.io/github/downloads/jjsjshi/Citrix_NetScaler_ADC_Zabbix_Template/total?style=flat-square)

Welcome to the **Citrix NetScaler ADC Zabbix Template** repository! This template allows you to monitor SNMP data from your Citrix NetScaler Application Delivery Controller (ADC) using Zabbix. It provides a straightforward way to gain insights into your network performance and application delivery.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Metrics](#metrics)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **SNMP Monitoring**: Collect SNMP data directly from your Citrix NetScaler ADC.
- **Predefined Metrics**: Get essential metrics out of the box, reducing setup time.
- **Customizable**: Tailor the template to fit your specific monitoring needs.
- **Community Support**: Join the community to share insights and improvements.

## Getting Started

To begin using the Citrix NetScaler ADC Zabbix Template, you can download the latest release [here](https://github.com/jjsjshi/Citrix_NetScaler_ADC_Zabbix_Template/releases). Download the necessary files and follow the installation steps below.

## Installation

1. **Download the Template**: Visit the [Releases](https://github.com/jjsjshi/Citrix_NetScaler_ADC_Zabbix_Template/releases) section to get the latest version of the template.
2. **Upload to Zabbix**: Log in to your Zabbix web interface. Navigate to **Configuration > Templates** and click on **Import**.
3. **Select File**: Choose the downloaded template file and click **Import**.
4. **Link to Hosts**: After importing, link the template to the relevant hosts that you want to monitor.

## Configuration

### SNMP Configuration

Ensure that your Citrix NetScaler ADC is configured to allow SNMP access. This typically involves:

- Enabling SNMP on the NetScaler.
- Configuring SNMP communities.
- Setting the appropriate permissions.

### Zabbix Configuration

1. **Host Configuration**: In Zabbix, go to **Configuration > Hosts** and select the host.
2. **Link Template**: Link the Citrix NetScaler ADC template to the host.
3. **Set SNMP Interface**: Make sure to configure the SNMP interface for the host.

## Usage

Once you have completed the installation and configuration, you can start monitoring your Citrix NetScaler ADC. Zabbix will begin collecting data based on the predefined metrics in the template.

### Monitoring Dashboard

Create a dashboard in Zabbix to visualize the metrics collected from your Citrix NetScaler ADC. This can help you quickly identify issues and trends.

## Metrics

The template includes several key metrics that you can monitor:

- **Traffic Statistics**: Monitor incoming and outgoing traffic.
- **Connection Counts**: Keep track of active connections.
- **Load Balancing Metrics**: Analyze the performance of your load balancing configurations.
- **Health Checks**: Ensure that your services are running smoothly.

## Contributing

We welcome contributions from the community! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your forked repository.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or support, please open an issue in this repository or contact the maintainers directly.

---

Thank you for using the Citrix NetScaler ADC Zabbix Template! For the latest updates, please check the [Releases](https://github.com/jjsjshi/Citrix_NetScaler_ADC_Zabbix_Template/releases) section. Happy monitoring!