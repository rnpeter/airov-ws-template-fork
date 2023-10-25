# Airov Workshop Site Template


## Getting started

This repository contains a snapshot of the AIROV web-page and a template for a workshop.

Please put your content into the folder

**pages/workshop/**

- Please do not rename the file `pages/workshop/workshop.md` - just edit the content. The file will be used as index page for your workshop.
- If you need more pages just copy the workshop.md file and edit it accordingly. **Note:** edit the last part of the permalink to the filename
- Note that any changes you make to files outside **pages/workshop** will be ignored.


## Testing the workshop webpage

If you want to test and see how the Workshop page look like you need following pre-requisites:

Ruby and Build Essentials:
```sudo apt-get install ruby-full build-essential zlib1g-dev```

Install Gems as user (not as root):

```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

Install Jekyll Bundler
```gem install jekyll bundler```


Change into this direcotry and build the page: ```jekyll b```

And have a look locally: ```jekyll serve```


## Auto-Deploy to https://airov.at

If you want to deploy to airov.at

- Contact simon.haller-seeber@uibk.ac.at and provide read access to your workshop git repository
- Enable the curl command in .gitlab-ci.yml  





