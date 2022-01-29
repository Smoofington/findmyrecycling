# Find My Recycling

---

Design Document

Matthew Caudill  
Hamza Rauf    
Daniel Cullen     
Jeffrey Benton     
Bhakti (lastname)

## Introduction

Do you want to recycle, but don’t know where to take it? Have harsh chemicals that you can’t put in the trash? FindMyRecycling can help you:
- Search for recycling centers near you
-	Save centers for easy access  

Use your android device to find recycling centers near you. Save your preferred facilities to your phone!

## Storyboard

storyboard goes here when finished

## Functional Requirements

## Requirement 100.0 Find my Recycling Center
#### Scenario  

As a user interested in recycling, I want to be able to search for recycling centers based on any part of the recyclable product’s name.  

#### Dependencies  

Recycling center data is available and accessible  

Device has GPS capabilities, and the user has granted access  

#### Assumptions  

Product names are in English  

#### Example  

1.1  

**Given** a feed of product data is available  

**When** I search for “motor oil”  

**Then** I should receive at least one result with these attributes   

	A facility to recycle motor oil  
	
1.2  

**Given** a feed of product data is available  

**When** I search “fluid”  

**Then** I should receive at least one result with these attributes  

	A facility to recycle Transmission fluid  
  
**And**  

	A facility to recycle Brake fluid  
  
1.3  

**Given** a feed of product data is available  

**When** I search “human remains”  

**Then** I should receive zero results (an empty list)

## Requirement 101.0: Save my center / save my search  

#### Scenario  

As a user interested in recycling, I want to be able to save my favorite facilities, and my favorite searches.  

#### Dependencies  

Recycling center data is available and accessible  

Device has GPS/address capabilities, and the user has granted access  

#### Assumptions  

Product names are in English  

2.1  

**Given** a user wants to save facility  

**When** facility is selected and a user signed in  

**Then** I should be able to do the following  

	You can save a facility to favorites

2.2  

**Given** a user wants to save facility  

**When** there is an active search and a user is signed in  

**Then** I should be able to do the following

	You can save the search to favorites  

## Class Diagram  

class diagram goes here when finished  

## Class Diagram Description  

## [Scrum](https://github.com/Smoofington/findmyrecycling/projects/1)  
DevOps/Scrum Master - Matthew Caudill  
UI Specialist(s) - Daniel Cullen  
Integration Specialist(s) - Hamza Rauf, Jeffrey Benton  

## [Github](https://github.com/Smoofington/findmyrecycling)  

## Weekly Meeting  
Tuesday and Saturday at 7pm EST on discord
