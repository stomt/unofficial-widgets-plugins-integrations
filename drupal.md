# Drupal Module

https://www.drupal.org/project/stomt
> Our Drupal Module allows to configure our javascript-widget in the Administration Interface of Drupal and then embeds the code on every page.


## Git 
- Website
 http://cgit.drupalcode.org/stomt

- Repo
 git://git.drupal.org/project/stomt.git

- Branches
 7.x-1.x = Drupal 7 compatible version
 8.x-1.x = Drupal 8 compatible version (default)

- Access
 Create an account on https://www.drupal.org/
 Get invited to STOMT project by Philipp or Max
 Add your public SSH key and choose a git username


## Development

- create local Drupal instance (e.g using docker) 
https://hub.docker.com/r/brunogoossens/dockercompose-drupal8/

- copy/clone (`[DRUPAL_GIT_USERNAME]@git.drupal.org:project/stomt.git`) the module to `[d8-root]/modules/*HERE*` 

- Install the extension

- Configure extension

- Validate your changes with the automated review tool https://pareview.sh/node/2677


## Release

- add a tag with the new release number. e.g. for version 1.2 
```
git tag 8.x-1.2
``` 
and push the new tag 
```
git push --tags
```

- select [add new release](https://www.drupal.org/node/add/project-release/2862228) and choose the new tag
