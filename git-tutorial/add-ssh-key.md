## Generating a new SSH key and adding it to the ssh-agent

1.Open Git Bash.
2.ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
3.When you're prompted to "Enter a file in which to save the key," press Enter. This accepts the default file location.
Enter a file in which to save the key (/c/Users/you/.ssh/id_rsa):[Press enter]
4.At the prompt, type a secure passphrase.
Enter passphrase (empty for no passphrase): [Type a passphrase]
Enter same passphrase again: [Type passphrase again]