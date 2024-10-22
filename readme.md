https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
```
cd ~/.ssh
```

```
ssh-keygen -t rsa -C "your-email-address" -f "github-username"
```

```
eval "$(ssh-agent -s)"
```

```
ssh-add -K ~/.ssh/github-rahul-office
```
