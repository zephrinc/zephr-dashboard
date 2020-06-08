# Zephr SaaS dashboard

## Intro
Project is based on https://preview.themeforest.net/item/flowdash-saas-admin-dashboard-template/full_screen_preview/25586651 to act as a static dashboard to demonstrate Zephr's applicability to SaaS customers.

## Devops
* Make all changes to *master* branch
* Any push to master will trigger a Github action that copies dist to the gh-pages branch (based on https://github.com/marketplace/actions/push-git-subdirectory-as-branch)
* This branch is connected to Github pages and changes will be reflected here: https://divydovy.github.io/zephr-dashboard/
