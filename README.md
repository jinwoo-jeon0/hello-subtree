# Add

```sh
git remote add hello-package https://github.com/jinwoo-jeon0/hello-package.git
git subtree add --prefix=src/hello-package hello-package master
```

or

```sh
git subtree add --prefix=hello-package https://github.com/jinwoo-jeon0/hello-package.git master
```

# Pull

```sh
git subtree pull --prefix=hello-package hello-package master
```
