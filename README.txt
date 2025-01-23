ANSIBLE FILTER AND LOOP EXAMPLES
==============================

A collection of example playbooks demonstrating Ansible filters and loops.

Files:
------
vars.yml         - Sample data structures used across playbooks
01_loops.yml     - Loop examples (loop, with_items, with_dict)
02_filters.yml   - Basic variable filters (upper, join, length)
03_map.yml       - Map filter examples and transformations
04_selectattr.yml - List filtering based on attributes
05_combined.yml  - Combined filter examples

Usage:
------
ansible-playbook <playbook_name>.yml

Examples:
---------
1. Basic loops:
   ansible-playbook 01_loops.yml
   Shows iteration over lists and dictionaries

2. Variable filters:
   ansible-playbook 02_filters.yml 
   Demonstrates string and list manipulations

3. Map operations:
   ansible-playbook 03_map.yml
   Shows attribute extraction and transformations

All playbooks include commented expected output for reference.

Documentation:
-------------
https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_loops.html
https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_filters.html 