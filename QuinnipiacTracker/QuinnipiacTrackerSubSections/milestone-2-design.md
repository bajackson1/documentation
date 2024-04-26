---
layout: default
title: Milestone 2 - Design Report
parent: Quinnipiac Tracker
nav_order: 3
permalink: /QuinnipiacTracker/Milestone2DesignReport
---

## Table of contents

{: .no_toc .text-delta }

1. TOC
{:toc}

---

Note: this is an updated version of [Milestone 1 - Design Report](../QuinnipiacTrackerSubSections/milestone-1-design.md) as we forgot to add some additional details.

# Milestone 2 - Design Report

## Navigvation Map

![nav.png](/assets/images/nav.png)

We want each screen to be able to go to each other, rather than one screen only being able to move to another. This way you can show ease of access to each screen, and not rely on one page to move around our app. Each part of the bottom toolbar will go to the following screens; Home goes to the home page, Info goes to the Mount Carmel Campus buildings page, Favs goes to the user’s favorites page, and Help goes to the help page. Each part will be able to move to another, and each label represents each of the different fragments used.

## MarvelApp UI

<https://marvelapp.com/prototype/6h3148h>

## User Story Table

| Wireframe | Associated User Stories |
| :--: | :--: |
| ![homewire.png](/assets/images/homewire.png)| As a user, I want to see a map of the Mount Carmel Campus, so I can know where each building is <br/><br/> As a user, I want to see my progress of where I have been on campus, so I can look back and refer to them for future purposes |
| ![infowire.png](/assets/images/infowire.png) ![info2wire.png](/assets/images/info2wire.png) | As a user, I want to see a list of all of the different academic buildings on the Mount Carmel campus with descriptions, so I can know more information about which building is which <br/><br/> As a user, I want to see a list of all of the different residence halls on the Mount Carmel campus with descriptions, so I can know more information about which hall is for who <br/><br/> As a user, I want to see a list of all of the different dining halls on the Mount Carmel campus with descriptions, so I can know more information about which ones are which |
| ![favswire.png](/assets/images/favswire.png) | As a user, I want to save a list of buildings on campus, so I can refer to those buildings later <br/><br/> As a user, I want to see my progress of where I have been on campus, so I can look back and refer to them for future purposes |

## System Design - ERD

![ERD1.png](/assets/images/ERD1.png)
![ERD2.png](/assets/images/ERD2.png)

## System Design - UML

![mile2UML.png](/assets/images/mile2UML.png)

The UML diagram shows the campus information system which lets users explore the buildings, facilities, and resources on the Mount Carmel campus. The main entities are AcademicBuilding, ResidenceHall, and DiningHall, all of which contain the name and description as well as aspects specific to each one (cuisine, capacity, etc.) The CampusMap class shows each building’s location and the UserProfile class tracks user interactions such as saved, visited, and favorite buildings. The user interface is split into BuildingListView, BuildingDetailsView, CampusMapView, and UserProfileView, enabling users to access and interact with the campus information. The relationships between the classes and their methods show information and interactions within the system, allowing users to manage and explore the Mount Carmel campus.

## Sprint Iterations

Here are our plans for the next Sprint Implementations with screenshots of our Trello board. We used the different tags based on riskiness of implementation. Here is the link: <https://trello.com/b/TlMqxrnk/final-project>

### Implementation 1

- As a user, I want to see a list of all of the different academic buildings on the Mount Carmel campus with descriptions, so I can know more information about which building is which
- As a user, I want to see a map of the Mount Carmel Campus, so I can know where each building is

![sprint1us.png](/assets/images/sprint1us.png)

### Implementation 2

- As a user, I want to save a list of buildings on campus, so I can refer to those buildings later
- As a user, I want to see my progress of where I have been on campus, so I can look back and refer to them for future purposes

![sprint3us.png](/assets/images/sprint3us.png)

### Implementation 3

- As a user, I want to see a list of all of the different residence halls on the Mount Carmel campus with descriptions, so I can know more information about which hall is for who
- As a user, I want to see a list of all of the different dining halls on the Mount Carmel campus with descriptions, so I can know more information about which ones are which

![sprint2us.png](/assets/images/sprint2us.png)