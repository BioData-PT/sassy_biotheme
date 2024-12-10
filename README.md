# Sassy Biotheme

Drupal theme that powers the [BioData.pt](https://biodata.pt) website.
Based on the [SASS Starter Kit](https://www.drupal.org/project/bootstrap_sass) for the [Barrio Bootstrap 5 theme](https://www.drupal.org/project/bootstrap_barrio)

## Setting up development environment
1. Install Node.js 22. The recommended way is to install [nvm](https://github.com/nvm-sh/nvm) and then run `nvm use 22` on the project's root directory.
2. Run `npm install` on the project's root directory.
3. Ensure the [`boostrap_barrio`](https://git.drupalcode.org/project/bootstrap_barrio) files are available at `../../contrib/bootstrap_bariro`.

## Compiling
Run `gulp js` and `gulp styles` to compile. **Compile before committing**, as CI does not perform any compilations.

## Deploy
GitHub Actions CI automatically deploys files to server.
