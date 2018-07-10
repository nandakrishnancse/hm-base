HM Base
=======

[![CircleCI](https://circleci.com/gh/humanmade/hm-base.png)](https://circleci.com/gh/humanmade/hm-base)

Standard WordPress layout for Human Made projects.

**Replace this readme in your project; you can use [the readme generator](https://humanmade.github.io/readme-creator/) for this.**

### Setup Instructions.

```sh
# Clone this repository:
git clone --recursive git://github.com/humanmade/hm-base.git your-project-name

# Navigate to the new directory.
cd your-project-name

# Remove the hm-base remote:
git remote rm origin

# Add the remote for your new project:
git remote add origin git@github.com:humanmade/your-project-name.git

# Push to the new remote
git push origin master

# Add a local config:
cp wp-config-local-sample.php wp-config-local.php
```

### Notes

* HM Base sets the MU Plugins directory to `plugins-mu` instead of `mu-plugins` for consistency.

## Contribution guidelines ##

see https://github.com/humanmade/hm-base/blob/master/CONTRIBUTING.md
