# buildpack-note

# commands

set defaul buildpack builder
```bash
pack set-default-builder cloudfoundry/cnb:cflinuxfs3
pack set-default-builder heroku/buildpacks:18
```

build
```bash
pack build test-ruby-app --path ./ws/sample-app --buildpack ./ws/cnb
```

# ref
https://buildpacks.io/docs/buildpack-author-guide/create-buildpack/setup-local-environment/
https://devcenter.heroku.com/articles/buildpacks

