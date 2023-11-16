# cptc-tools
CPTC Globals tooling for C3T. This repo will be set to read only and a request will be submitted NLT Friday December 29, 2023 IOT comply with the CPTC Globals rules

From CPTC ROE:
"The Operations Team must be provided a request for access to or the creation of a repository for
approval prior to the competition. The submission deadline will be a minimum of two (2) weeks
prior to any CPTC event."

# Config Wizard (config.py)

A wizard to help you set the IP address ranges and hosts in scope for the competition. This will generate a config file that can be used by the other tools.

# Installation Script (install.sh)

A script to install all the packages needed for the tools to run. This script is intended to be run on a fresh install of Kali Linux.

# Super Nmap (super_nmap.py)

 A wrapper for nmap that automatically converts the output to html and caches hosts in the config file for more scans.

 Run `python3 super_nmap.py -h` for help
