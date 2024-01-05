# Fransible

This playbook is intented to complement the [`lalubuntu` playbooks](https://github.com/laluka/lalubuntu), adding some cool tools that I use on a daily base.

## This playbook is only intended to be run in `Ubuntu 22.04`

## Sum-Up

The ansible playbook main.yml applies 4 ansible tasks which are:

- tasks/install-spotify
- tasks/install-obsidian
- tasks/install-exegol
- tasks/cleanup

##  Install

```bash
git clone https://github.com/fransosiche/fransible
sudo mv fransible /opt/fransible
cd /opt/fransible
ansible-playbook -vvv -i inventory.ini --ask-become main.yml
```

## What's getting installed ?

1. **Exegol** because exegol is a pure banger
2. **Obsidian** cause cool tools for notes
3. **Spotify** because musics