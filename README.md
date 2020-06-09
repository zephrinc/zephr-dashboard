# Zephr SaaS dashboard

## Intro
Project is based on https://preview.themeforest.net/item/flowdash-saas-admin-dashboard-template/full_screen_preview/25586651 to act as a static dashboard to demonstrate Zephr's applicability to SaaS customers.

## Devops
* Make all changes to *master* branch
* Any push to master will trigger a Github action that copies dist to the gh-pages branch (based on https://github.com/marketplace/actions/push-git-subdirectory-as-branch)
* This branch is connected to Github pages and changes will be reflected here: https://divydovy.github.io/zephr-dashboard/

## Zephr-specific changes
1. Sign up / sign in template is zephr-signup.html (here: https://divydovy.github.io/zephr-dashboard/zephr-signup.html)
2. Locked replacement for a component is zephr-index.html (here: https://divydovy.github.io/zephr-dashboard/zephr-index.html)
3. Nudge is in the LH sidebar on index page above
4. LH menu is stripped back 
5. Locked component is zephr-panel.html (here: https://divydovy.github.io/zephr-dashboard/zephr-panel.html)

## To do
1. Fix NPM build and replace dist changes with source changes (waiting on ticket back from developer on NPM errors)