# Welcome to QuickStatements 3.0

*This is the new version of QuickStatements tool (v3), launched on October 2024*

## Objective and usage

The objective of Quickstatements v3 is to enhance the functionality, performance, and user experience of the QuickStatements platform.

Quickstatements is a widely used tool for inserting and modifying data on [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page), one of Wikimedia's platforms.

## Authentication and authorization

In order to use the QuickStatements platform, you must be authenticated and authorized to use the platform. This application uses OAuth2 with the Mediawiki provider. You can find more details of how to request access in the Readme file.

## Components

This version contains 2 main parts:

### A. The navigation bar

It is positioned at the top of the page and provides quick links to the most used parts of Quickstatements tool.

> #### 1. QuickStatements 3.0 link
Positioned at the top left corner, it takes you to the homepage.
> #### 2. New batch link
Positioned next to the QuickStatements 3.0 link, it takes you to the batch/new/ endpoint, where you can submit a new batch.
> #### 3. Last batches link
Positioned next to New batch link, it takes you to the batches/ endpoint, where you can currently view the list of the last 20 modified batches.
> #### 4. Git link
Positioned next to the Last batches link, it takes you to the github repository of the Quickstatements3 project.
> #### 5. User:username | Login link
Positioned in the top right corner, it shows your username and takes you to the user profile page, if you are authenticated, otherwise the Login link is displayed, which takes you to the login page.
> #### 6. Your last batches link
Positioned next to the User:username | Login link, it takes you to the batches/\<str:user\>/ endpoint, where you can currently view the list of your last 20 modified batches.

### B. The batch related content

This part includes 3 main features.

> #### 1. Creating new batch of data

This component is composed of a button located in the homepage of the tool, which takes you to the batch/new/ endpoint, where you can submit a new batch.

> #### 2. Searching for a specific batch of data based on batch id

The tool allows you to enter the batch id for which you want to view the related details in a separate page.

> #### 3. Searching for related batches of data based on username

The tool allows you to enter a username and filter the submitted batches respective to this username.

