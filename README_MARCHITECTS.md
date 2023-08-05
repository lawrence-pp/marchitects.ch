<h1 align="center">marchitects.ch</h1>

<p align="center">
    Hubspot webpage marchitects.ch
</p>

## Getting started

The marchitects.ch webpage is a fork of the [HubSpot CMS Boilerplate](https://designers.hubspot.com/docs/building-blocks/themes/hubspot-cms-boilerplate) repository. 
It uses version control using GitHub and GitHub Actions to deploy the project to Hubspot (see corresponding section in README_HUBSPOT_CMS_BOILERPLATE.md).

The marchitects.ch webpage is built by Partner & Partner AG in Winterthur, Switzerland. 
Developer: [Lawrence Markwalder](mailto:markwalder@partner-partner.ch)

## Deploy changes

Changes are deployed whenever they are merged into the main branch.

## Development

`hs --mode=draft watch ./src  marchitects.ch`

Local development in a Hubspot context means that you upload your local files to Hubspot and use your Hubspot account to preview your page. 
In our setup we automatically sync our local code with Hupspot, i.e. you can view the updated files in Hubpsot Design Manager. To avoid to immediately publish changes, we run the Hubspot watch command in draft mode: `hs --mode=draft watch ./src  marchitects.ch`.

Changes can be published either manually (publish button in Hubspot) or via GitHub actions by pushing to the main branch.


