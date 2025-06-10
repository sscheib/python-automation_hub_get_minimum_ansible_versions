# About
This script iterates through all Ansible Collections which are available from the Ansible Automation 
Hub (console.redhat.com) in both the validated content and the certified content and prints out the
minimal required Ansible Core version for the latest available collection version.

Optionally, the data can be written to a spreadsheet (.xlsx).

# Get started
```
pip3 install -r requirements.txt
python3 automation_hub_gather_minimal_ansible_version.py <your commandline arguments here>
```
