# Introduction 

## How to see the website after changes
1. Local version
    - This works for Unix-like terminals/MacOS terminals. Navigate to the main folder (something like csulb-nanoelectronics.github.io) and open it up in terminal. Then run `bundle exec jekyll serve' which will open a local jekyll server that performs the rendering. To view the website, then go to a web browser and type in 'http://localhost:4000/'
    - Note: anytime you make a change to _config.yml (which will likely happen when you need to add another tile/main folder to the main homepage), you'll need to restart the jekyll server (ctrl + c to quit and run 'bundle exec jekyll serve' again to restart) 
2. Github/public version
    - This is the version on the actual website. You'll need to push your changes to the main branch of github and then wait for anywhere up to 10 minutes for changes to update. Website link is at: csulb-nanoelectronics.github.io 


## Homepage 
The homepage consists of a bunch of tiles, each of which is a clickable link. These tiles correspond to each machine/topic of interest in the lab. Clicking on these tiles will then lead to a "subfolder" which contains the SOP's specific to each machine. 

Example. 
- The first square at the time of writing this is "Oxford Teslatron PT Closed Cycle Cryostat" with a picture of the cryostat. Clicking on it will lead to a subfolder with more tiles. Each tile then corresponds to a specific procedure ie, "Warmup", "Cooldown", etc. 

### Modifications/Code 
To add a square to this main front page (such as when wanting to add a new machine, but not a specific SOP for an existing machine, see below), go to the csulb-nanoelectronics.github.io folder. This is assuming that you already have Github installed on your computer signed into the student nanoelectronics account (with a local copy of the repository). When in doubt, make a new branch to work on to test changes before pushing to the main branch. 

Once there, go to """my_collections""" and then `_portfolio'. 

