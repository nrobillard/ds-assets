# ds-assets
This repository contains the assets for the data science notebooks in the ds-notes repository.

The content in the assets folder is made accessible in notebooks through the following
preamble,
```
###### Set Up #####
# verify our folder with the data and module assets is installed
# if it is installed make sure it is the latest
!test -e ds-assets && cd ds-assets && git pull && cd ..
# if it is not installed clone it 
!test ! -e ds-assets && git clone https://github.com/nrobillard/ds-assets.git
# point to the folder with the assets
path = "ds-assets/assets/" 
import sys
sys.path.append(path)      # add home folder to module search path
```

