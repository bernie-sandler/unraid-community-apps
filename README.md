# Unraid Templates
A collection of Community Applications for [Unraid](https://unraid.net/), maintained by me.

The repository provides Docker application templates to simplify deployment and management through Unraid's Community Applications system.


## Repository Structure
```text
unraid-community-apps/
├── templates/
│   ├── belltower.xml
│   └── etc...
├── plugins/
│   └── plugin-templates.xml
├── .gitignore
├── ca_profile.xml
├── LICENSE
├── logo.png
└── README.md
```


## Available Applications
Applications will be listed here as they are added.
|Application|Description|Status|
|---|---|---|
|[Belltower](https://github.com/bernie-sandler/Belltower)|Self-hosted ticketing for homelabs and small teams. Ring the bell when something breaks.|![Status](https://img.shields.io/badge/Released-In_Development-007ec6?labelColor=2ea44f)|


## Installation
1. Open Community Applications in Unraid.
2. Navigate tp the Previous Apps / Settings area, depending on your Unraid version.
3. Add this repository as a custom template repository:
   - Repository URL: `https://github.com/bernie-sandler/unraid-community-apps'
4. Return to Community Applications.
5. Search for the application you want to install and click "Install".


## Support
For support, please open an issue in any of the following application repositories or contact me directly.


## Disclaimer
These templates are provided as-is. Application functionality, availability, and maintenance depend on their respective upstream projects.

Always review container configurations before deployment.


## License
See [LICENSE](LICENSE) for license information.
