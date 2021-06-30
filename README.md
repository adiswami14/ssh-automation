# ssh-automation
Using Ansible to generate and deploy SSH Keys on remote servers.

Followed XavkiEn's YouTube tutorial on how to generate and deploy SSH modules.

This piece of code will just generate a random ssh key, and then deploy that key to create a user on a specific host (in this case, we use a mock host given to us by Docker). Then, we can ssh in to that server with our particular user whenever we want. Currently, the name is just "user". We also give the user sudoer privelege within the server.
