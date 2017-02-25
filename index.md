# Isard VDI
IsardVDI was born with the goal of creating a free software alternative to solutions such as Citrix XenDesktops or VMware Horizon in deploying virtual desktops.

IsardVDI directly manages KVM Linux hypervisors using libvirt.

A web application allows agile deployments of desktops and manage hypervisors.

## Screenshots
User desktops

![Desktops](content/img/isard_desktops.png)

User templates

![Templates](content/img/isard_templates.png)

User uploaded iso files

![Isos](content/img/isard_isos.png)

User quotas for desktops, templates and isos

![Quotas](content/img/isard_quotas.png)

Number of desktops running in our real system per hypervisor

![Load](content/img/isard_dayload.png)


## Features
##### Benefits to users
+ Linux and Windows virtual desktops
+ Template creation from desktop snapshot
+ Template shareable with other users and groups
+ Web interface real time events for improved user experience [![Sample](content/img/isard_dayload)](content/img/isard_dayload.png)
+ Spice, HTML5, VNC and rDesktop viewers available
+ USB devices redirection in spice viewer
+ Kiosk mode. Create disposable desktops
+ Multiple esoure permission levels
+ Quotas for desktops, running desktops, templates and isos

##### Benefits to administrators
+ Not tied to any propietary hardware.
+ Not tied to any hypervisor/nas distro
+ Desktops small disk footprint (we handle over 1400 desktops in 5TB)
+ Hypervisors can be grouped in pools 
+ Manage thousands of desktops from a single dashboard
+ User access management with database, ldap, oauth2, ...
+ Quotas at roles, categories, groups and user levels
+ Granular permissions for all resources
+ Customizable distributed storage for better performance
+ Two level cache system
+ Kiosk mode, with customized templates and menus based on networks
+ Vlan mapping per virtual desktop
+ High end nginx performance proxy ready
+ Available cluster database backend
+ Grafana module included
+ Continuous development and test in real production environtment

#### Future lines

#### Success story

We are currently developing new features and continuosly testing it in a real production environtment with more than 900 users and more than 1400 virtual desktops in system using it.

### Authors
+ Josep Maria Viñolas Auquer
+ Alberto Larraz Dalmases

### Support/Contact
Please send us an email to isard.vdi@gmail.com if you have any questions 
