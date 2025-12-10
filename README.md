# ATTENTION

This role is replaces rules files in /etc/ufw. It potentially logs you out of the remote system!

So far my approach to use this rule is:

- Use the ufw command to create the rules.
- Copy the rules files to the ansible directory (as a backup or template)
- Distribute the files using this roles to machines with the same setup & environment

# LINKS

- https://manpages.debian.org/trixie/ufw/ufw.8.en.html
- https://manpages.debian.org/trixie/ufw/ufw-framework.8.en.html