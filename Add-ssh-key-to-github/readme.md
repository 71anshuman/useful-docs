## Add SSH Keys to Github

### Generate SSH Key
- `ssh-keygen -t rsa -C "email@test.com"` replace `email@test.com` to your github email address.
- Then it will ask for `Enter file in which to save the key (/Users/<Your username>/.ssh/id_rsa):`, just hit `Return / ENTER`
- Then it will ask for `Enter passphrase (empty for no passphrase):`, just hit `Return / ENTER` - `x2`
Now, your keys has been generated and it is that easy.

### View your SSH key using
- `cat ~/.ssh/id_rsa.pub`
- Copy the SSH key

### Add Key to Github
- Go to [Github Settings](https://github.com/settings/keys)
- Click `New SSH Key`
- Paste the key under textarea labeled `Key`
- Also, you can add title for the device, which will help you know which key has been used.


