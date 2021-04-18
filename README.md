# Overview
Ansible playbook to get an installation of Fedora 33 KDE up to baseline. What that means is different for everyone but for me that implies:
* removing un-needed packages (calligra-\*, kf5-akonadi-\*, kde-connect, plasma-discover etc);
* installing needed packages (libreoffice, vlc etc)
* disabling un-needed services (avahi, baloo);
* configuring services how I like them (konsole, fish, vnc);


# Installation
* install ansible: `dnf install ansible`
* run playbook: `sudo ansible-playbook main.yml`
