larasis
=======

## GIT WORKFLOW
```shell
## CLONE REPO (ONLY on FIRST TIME)
git clone git@github.com:sithesis/larasis.git

## UPDATE CODE (ONLY IF NOT FIRST TIME)
git pull origin master

## EDIT CODE WITH YOUR EDITOR
vim app/controllers/BlahBlahController.php

## ADD CHANGES TO COMMIT
git add app/controllers/BlahBlahController.php

## COMMIT THE CHANGES to LOCAL REPO
git commit -m "I Updated the BLAh2x Controller"

## PUSH changes that you committed
git push origin master
```

## NOTES:
```shell
# INSTALL COMPOSER
https://getcomposer.org/Composer-Setup.exe


# DOWNLOAD/INSTALL LARAVEL
composer global require "laravel/installer=~1.1"


# CREATE PROJECT (ONLY FOR FIRST TIME)
# REQUIRES: php5-mcrypt MODULE
composer create-project laravel/laravel your-project-name --prefer-dist

# GITHUB SETUP TURORIAL
https://help.github.com/articles/generating-ssh-keys/#platform-windows

# DOWLOAD the GIT repo
git clone git@github.com:sithesis/larasis.git      # WHEN USING SSH-KEY
git clone https://github.com/sithesis/larasis.git  # USING username & password
```
