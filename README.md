# Aplia eZ JS Core (fork of eZ JS Core )

## What is Aplia eZ JS Core?

Aplia eZ JS Core is a fork of eZ JS Core extension which is bundled inside the eZ Publish legacy repository.

#### How to merge with eZ JS Core

1. Checkout `ezpublish-legacy`

   `git clone https://github.com/ezsystems/ezpublish-legacy`

2. Checkout Aplia eZ JS Core

   `git clone git@github.com:Aplia/ezjscore.git aplia-ezjscore`

3. Enter Aplia eZ JS Core

   `cd aplia-ezjscore`

4. Remove everything except `.git`, `README.md` and `composer.json`

   `ls | grep -v '.git' | grep -v 'README.md' | grep -v 'composer.json' | xargs rm -R`

5. Copy updated code from `ezpublish-legacy`

   `cp -R ../ezpublish-legacy/extension/ezjscore/ .`

6. Review and add changes

   `git add .`

7. Push code and add new release
