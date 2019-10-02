# Ansible-Arcade

This Github repository is for the Ansible Arcade Project.  This project is meant to serve as a hands-on demonstration of Ansible capabilities through self-led technical challenges.  Unlike conventional demos an attendee has limited oversight or instruction from a human.

There are several philosophies of this demo concept:

- Fun!  This project is meant to steal concepts from escape rooms and video games.
- Demonstration of IoT (Internet of Things) via Philips Hue smart light bulbs.
- Demonstration of other Red Hat products (e.g. Red Hat Enteprise Linux)
- Demonstration of multiple use-cases outside of Red Hat (Network, Windows, etc)
- Progressive problems that increase in difficulty.
- Gamification of winning, stickers and or other swag can be rewarded for solving the puzzle.
- Re-usability to augment the Red Hat Command line Heroes arcade cabinet ideas (see https://github.com/CommandLineHeroes)

# Challenges
There are a total of five challenges that need to be solved in order to complete the Ansible Arcade.

Five Ansible Playbooks has already been created:
- linux.yaml
- windows.yaml
- net-l2.yaml
- net-l3.yaml
- facts.yaml

The objective is to identify parameters that need to be fixed, added, and or deleted in order meet the requirements per challenge.

1. Linux (RHEL) - Inspect the module being utilized to figure out why the playbook is failing.
2. Windows - Identify the missing parameters to fullfil the requirements
3. Layer 2 - Utilize the data model to push the correct configuration to the Arista Device
4. Layer 3 - Utilize the data model to push the correct configuraiton to the Cisco Device
5. Facts - Identify the facts that are gathered to correctly populate the variables in values.j2

# Sponsored by

This project is sponsored by the Red Hat Ansible Automation Platform team:

![ansible platform logo](roles/website/files/webpage_logo.png)
