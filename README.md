[![DOI](https://zenodo.org/badge/574679318.svg)](https://zenodo.org/badge/latestdoi/574679318)

https://cu-mkp.github.io/dyngleyfamily-editioncrafter-website/

# EditionCrafter Website Repository for Dyngley Family
This is the repository for the website containing the Dyngley Family edition built with EditionCrafter. It contains the stub markdown pages and navigation for the websites.

- Hugo website template
- This can now be customized for content
- Under “Folios,” there is the rendered TEI file of the manuscript
- Took output of editioncrafter-cli and dropped into the dedicated directory of editioncrafter-project

# To create a website from this repository

- Fork this repository (you only need to copy the `main` branch)
- In your fork, update the `baseURL` in `config/production/config.toml` to reflect your organization and new repository name
- In your fork, update the markdown files in the `content` folder with your content. In particular make sure to update the information in `folios.md`
- If you only copied the main branch, at this point you should create a new branch called `dev`. This will have the effect of triggering a workflow that creates the files you'll need to deploy your site to GitHub Pages; those files live in a `gh-pages` branch, which will be created by the workflow
- Once the workflow is run and the `gh-pages` branch exists, go to the settings tab for your repo and select "Pages" from the menu on the left. Enable GitHub pages and set your site to deploy from a branch, and then select the `gh-pages` branch (and `/root`) folder. 
