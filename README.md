# Gitpod configuration for Shopware

This configuration was borrowed from `shyim` his awesome work, but adds a few tweaks (that worked for me).

## Setup
Clone this repository somewhere and copy the following files to your own Shopware project repository:

- `.gitpod.yml`
- `.gitpod.Dockerfile`

Next, within your **Dashboard** at Gitpod, under **Variables**, add a new variable `SHOPWARE_PACKAGES_SECRET` (for instance with scope `*/*`) with a value that reflects your Shopware Store token.

Make the repository available online (for instance, via a GitHub repository) and use Gitpod to run a pod with it.

## Todo
- Make this available as a separate Symfony Flex recipe
