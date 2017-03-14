# nubis-accounts-webops
WebOps Nubis Accounts

### Adding submodule for new projects
If you have a new account you need to add the nubis-deploy module to the path

```
git submodule add http://github.com/nubisproject/nubis-deploy.git accounts/<your account name here>/deploy
```

### Updating submodule
When the submodules are updated you will need to update the submodule as well

```
git submodule update --init
```
