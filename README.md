# TroutSGM

## UseCase  
Style guides are created by UI/UX designers using softwares like figma, adobeXD, invision, etc. These style guides are translated into reusuable code with the aid of developers. Thus, increasing the dependency of UI/UX designers on the development team. The idea of this project is to create a interface with following capabilities
- Allow UI/UX designers to maintain style guides in indepedence of development team
- Translate style guides into .css file to be used by the development team
- Delivery of .css by downloding file, over cdn or other means
- Create web page of style guide to be used by other teams
- Version control

## UseCase-1: Manage style guide

The idea is to give a user interface to the UI/UX designers to 
- Add/delete html elements to the style guide
- Add/update css properities to the html elememnts
- visualize the style of the elements
- Assign class names to the elements

## UseCase-2: Generate & deliver CSS
The elements, their css properties and class names are stored in the database. These designes will be used by UI developers. Instead of using copy-paste of css properities, the developers will be able to generate the .css file of the elements defined by the UI/UX designer. Which can be later downloaded or inculded in the codebase via CDN link

## UseCase-3: Style guide webpage
To present the style guide to the internal as well as external stakeholders, the style guide needs to be rendered into a webpage which is piublically hosted.

## UseCase-4: Version control
This capability will allow the UI/UX team to
- Track the evolution fo style guide
- Contributor management
- Rollback guides

