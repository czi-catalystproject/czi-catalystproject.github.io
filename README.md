# The Catalyst Project Website

This repo contains the Jupyter Book source files for the [catalystproject.cloud](#) brochure site.

## About

Our goal is to create a collaborative cloud infrastructure service that enables community-based cloud-native workflows in the biosciences. We will promote values of open and inclusive community practices, infrastructure that enables these practices, and a “train the trainers” approach that empowers community leaders to share expertise in cloud infrastructure with others in their communities. Our focus will be on communities in Latin America and Africa, and we hope to learn how this model could be extended to other global communities that are historically marginalized from large-scale scientific infrastructure projects[^1].

## Getting Started

We recommend editing the contents of this repo using the 2i2c Community Showcase Hub.

> [!INFO]
> If you require collaborator access to this repo, please [Get in Touch](#get-in-touch).

1. Access the 2i2c Community Showcase Hub at [https://showcase.2i2c.cloud/](https://showcase.2i2c.cloud/). If you require authorisation to access this hub, please [Get in Touch](#get-in-touch).

1. Select the *Shared Small: 1-4 CPU, 8-32 GB* server option and in the *Image* dropdown box select *Handbook Authoring*.

1. Once the JupyterLab interface has loaded, set up GitHub authentication with `gh-scoped-creds`. This allows you to pull and push to GitHub repos. To enable this, open a terminal, run the command

   ```shell
   jovyan@jupyter-user:~$ gh-scoped-creds
   ```
   
   and follow the prompts to enter your code at [https://github.com/login/device](https://github.com/login/device)

   > [!CAUTION]
   > We do not recommend entering your GitHub credentials (GitHub password, personal access tokens or otherwise) on any kind of shared infrastructure (e.g. private and public cloud, HPC, any remote machine) as this information will be at risk. We highly advise using `gh-scoped-creds` for authentication on our hubs. Read [this article](https://blog.jupyter.org/securely-pushing-to-github-from-a-jupyterhub-3ee42dfdc54f) for more information.

1. Git clone [this project repo](https://github.com/czi-catalystproject/website) using the Terminal with the command

   ```shell
   jovyan@jupyter-user:~$ git clone https://github.com/czi-catalystproject/website.git
   ```

1. Follow the [how-to-guide](https://2i2c.org/community-showcase/community/content/authoring.html) for authoring and previewing content using Jupyter Book.

### GitHub permissions for 2i2c-org and czi-catalystproject owners

These are extra instructions for GitHub [2i2c-org]https://github.com/2i2c-org and [czi-catalystproject](https://github.com/czi-catalystproject) owners to grant permissions.

#### Access to the Community Showcase Hub

Add the user to the `2i2c-org/Research-Delight-Team` for access.

#### Add collaborator to [this project repo](https://github.com/czi-catalystproject/website)

Go to the [GH repo](https://github.com/czi-catalystproject/website), click *Settings -> Access - Collaborators and teams* and add the relevant user or team. Assign the *Write* role in the first instance (can be upgraded later if needed).

#### `gh-scoped-creds` and GitHub App

The GitHub App [2i2c Community Showcase Hub](https://showcase.2i2c.cloud/) is currently installed on `czi-catalystproject/website` and `czi-catalystproject/hub-champion-training` to enable `gh-scoped-creds`.


## Get in Touch

To report an issue with the website or ask a question about the project, please [open an issue](https://github.com/czi-catalystproject/catalyst-project/issues/new/choose) or send a message to <catalyst-project-core-team@googlegroups.com>.

[^1]: "New project: Open science cloud infrastructure and training for communities in Latin America and Africa" by Chris Holdgraf, available under CC-BY 4.0 at the [2i2c blog](https://2i2c.org/blog/2022/czi-global-communities-announcement/).

