## Overview

ScytheEx is an advanced cybersecurity tool designed for real-time network traffic monitoring and threat analysis. Initially developed as a Linux service daemon and capable of deployment on Kubernetes bare metal, this versatile solution extends its functionality across various operating systems.

ScytheEx integrates AI-driven analytics to detect activities post-attack, adhering to the philosophy that despite advanced protective measures like EDR or AV, malware may still execute on the system. The tool operates at this post-execution level to identify malicious activities and generate YARA rules, providing continuous feeds to enhance other detection tools and technologies.

> [!Warning]
> ScytheEx-Legacy is archived as it has reached its final development phase which is a proof of concept for our XDR, the team is currently working on developing the final product.

### Main Features

- AI-powered network traffic analysis.
- Real-time threat detection and mitigation.
- Background process management for continuous monitoring.
- Integrated threat intelligence.
- Robust mitigation strategies including IP blacklisting.
- Customizable configuration to fit your business need.
- HTTP Server for visualization.
- Support for Kubernetes deployments.
- 3rd Party APIs usage (e.g: Virus Total, Hybrid-Analysis)


### Kubernetes Deployment using Helm

> [!Important]
> By default, **ScytheEx** runs as a daemonset on Kubernetes and is not fully tested which may break; Kubernetes admins can customize the deployment as needed.

## How to Contribute

This repo is now archived. However, you will be able to contribute to the full version shortly :)

## License

This project is licensed under the GNU General Public License v3.0. For more details, see the LICENSE file in the root directory of this project.
