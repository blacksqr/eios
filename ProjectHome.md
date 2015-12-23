Eios is an ssh and telnet automation tool

Eios uses your existing client to connect and log in to remote devices and manage interaction

The eios design goals are fast, flexible & secure.

It is intended as both your every day login client, and a bulk operations script.

Unlike many similar scripts, eios goes well beyond simply automating logins and/or running commands from a file. For example, eios can execute any number of commands on the remote host and return the output directly to the shell. You can configure certain command be always be run upon login, before handing interactive control of the device back to you. eios produces very clean output, all of which can be logged.

After configuring your user profile and hostsfile, logging in to any of your devices is as simple as 'eios mydevice'. Running multiple commands is as easy as 'eios mydevice show version % show clock'. The hostsfile - which optionally contains all your login details - can be AES encrypted to protect your credentials. You are then prompted to decrypt the file at runtime ensuring that passwords to do not appear in active processes.

eios comes with a large number of options, all of which can be stored per-user or per-host or per-group-of-hosts.

eios can understand and interact with many types of network devices 'out of the box' and is designed to be easy to extend via device profiles. It can be configured to work with almost any device offering a terminal interface

There are many more features to eios, please read the included documentation to find out more.