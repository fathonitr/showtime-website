+++
title = "Features"
weight = 1
+++

{{<section title="App">}}

[//]: # (TODO: add screenshots)

## Home screen

One of the core features of the App is the map where users can see their position and all the available points of interest (POI) are indicated with markers. The markers are shown in different colors acoording to the category of the POI. Categories are used to group POI by similar histories. Clicking on a marker will navigate to the detail view of that POI.

Underneath the Map is a modal with a list of all the available POI. For each place it shows the name, address, distance and available media. If users are searching for a particular place they can use the search input to find it. Selecting a place also opens the detail view.
{{<image src="app-home.jpg" alt="app home screen" caption="Home Screen">}}

## Detailed Information about a place

The detail view of a POI shows all the available information and media about the place. At the top it shows the name, an image, the address and the address description. Below that is a text description, audio and a gallery of all the images if alvailable.
At the top users can save their favourite places by marking them with a star. They can also share places with friends via the native share feature.
{{<image src="app-detail.gif" alt="app detail" caption="Detail View">}}

## Notifications based on Geolocation

While the app is running in the background it accesses the location of the user to send a local notification to them when they are close to a POI. Clicking the notification will open the app and show the detail view of that POI. The app will only send one notification per POI in a session.

In Android the app will show a notification for the whole time it is running in the background. In iOS the geolocation access is indicated while the app is running in the foreground and background.

## Filtering

Via the menu button on the Home screen users can filter POI. They can be filtered by radius around the current position of the user and by categories. In the Filter screen users can also choose to only show the POI they marked as favourites.
{{<image src="app-filter.jpg" alt="app filter" caption="Filter">}}

## Settings

The settings, which are also accessed via the menu button, allow users to turn notifications on or off. To filter notifications they can choose to only turn on notifications for certain categories. It is also possible to change the language in the settings.
{{<image src="app-settings.jpg" alt="app settings" caption="Settings">}}


## App introduction and help

When users first open the app, they are greeted with introductory slides that give a short overview of the features of the app. The last slide lets the users know that they should close the app properly after they are done using it, so that it does not keep running in the background.
{{<image src="app-walkthrough.jpg" alt="app introduction screens" caption="Introduction">}}

Users can access a help popover via the menu button. The popover explains the use of categories and their colors and allows them to view the introduction slides again.
{{<image src="app-help.jpg" alt="app help popover" caption="Help Popover">}}

{{</section>}}

{{<section title="Editor">}}

## Authentification

The different institutions we work with each have to register for an account where they then can set their default language, and create pois and categories.
{{<image src="authentification.PNG" alt="login screen" caption="Login Screen">}}

## Homescreen with filtering of POIs

## Create POIs by category
Each editor can create categories with a specific color in which they later can assign pois to (e.g Queerwalk, forced labor in Berlin, etc). The pois contain an address, an address description, a description and assets (text, audio, video and images). The address can be typed in or set by clicking on a location on the map.

{{<image src="poi-creation.PNG" alt="editor poi creation" caption="POI Creation">}}

## Interactive Map

## POI detail preview

{{<image src="poi-detail-de.PNG" alt="editor poi detail de" caption="German">}}


## Multi-language support

Our WH2 Editor provides the possibility to not only to be used in multiple languages but further more also allows the editors to create pois, categories and their assets in those. Currently we support english and german.

{{</section>}}