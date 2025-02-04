# Mordor Gates

![mordor_logo](./docs/source/_static/mordor-logo.png)

The Mordor project provides pre-recorded security events generated by simulated adversarial techniques in the form of JavaScript Object Notation (JSON) files for easy consumption. The pre-recorded data is categorized by platforms, adversary groups, tactics and techniques defined by the Mitre [ATT&CK Framework](https://attack.mitre.org/wiki/Main_Page). The pre-recorded data represents not only specific known malicious events but additional context/events that occur around it. This is done on purpose so that you can test creative correlations across diverse data sources, enhancing your detection strategy and potentially reducing the number of false positives in your own environment.

The name **Mordor** comes from the awesome book/film series "[The Lord of the Rings](https://en.wikipedia.org/wiki/The_Lord_of_the_Rings_(film_series))", and it was a place where the evil forces of [Sauron](https://en.wikipedia.org/wiki/Sauron) lived. This repository is where data generated by known "malicious" adversarial activity lives, hence the name of the project.

<img src="https://media.giphy.com/media/26uN0fPodsblcQ2V8S/giphy.gif" width="980" />

# Goals

* Provide free portable malicious datasets to expedite the development of data analytics.
* Facilitate adversarial techniques simulation and output consumption.
* Allow security analysts to test their skills with real known bad data.
* Improve the testing of hunting use cases and data analytics in an easier and more affordable way.
* Enable data scientists to have semi-labeled data for initial research.
* Map threat hunter playbooks to their respective pre-recorded data for validation purposes.
* Contribute to the [ATT&CK framework](https://attack.mitre.org/wiki/Main_Page) **Data Sources** section of each technique and sub-technique.
* Ingest known bad data samples for training and capture the flag (CTF) events.
* Learn more about red team simulation exercises and technology such as Kafkacat, Kafka and Jupyter Notebooks.

# Getting Started

* [Available Networks](https://mordor.readthedocs.io/en/latest/network_available.html)
* [Mordor Datasets](https://mordor.readthedocs.io/en/latest/mordor_datasets.html)
* [Mordor Data Export](https://mordor.readthedocs.io/en/latest/export_mordor.html)
* [Mordor Data Import](https://mordor.readthedocs.io/en/latest/import_mordor.html)

# Projects Using Mordor

* [ThreatHunter-Playbook](https://github.com/Cyb3rWard0g/ThreatHunter-Playbook)
* [HELK](https://github.com/Cyb3rWard0g/HELK)

# Authors

* Roberto Rodriguez [@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g)
* Jose Luis Rodriguez [@Cyb3rPandaH](https://twitter.com/Cyb3rPandaH)

# Commiters
* Jonathan Johnson [@jsecurity101](https://twitter.com/jsecurity101) 
# Contributors

# Contributing

There are a few things that we would like to accomplish with this repo as shown in the To-Do list below. Share your pre-recorded data with us following our same setup (working on a standard setup..), and help others in the Cyber community to validate their detection use cases in a faster and easier way.  

# License: GPL-3.0

[ Mordor's GNU General Public License](https://github.com/Cyb3rWard0g/Mordor/blob/master/LICENSE)

# To-Do

- [ ] Dynamically generate mordor datasets readme files in restructuredtext
- [ ] Release environment scripts
- [ ] Add OSquery to endpoints for Linux/macOS
- [ ] Share Terraform & Packer config files to deploy the same environment in the cloud
- [ ] Add a Bro sensor
- [ ] Multiple custom network setup for contributions
- [ ] Add toolsets to the Empire box inside of AWS configuratons
- [X] Prepare Large Dataset ;)
- [X] Logo

More coming soon...
