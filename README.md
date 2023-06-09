# Creating-a-Master-Property-Listing-for-Listing
The goal of this project is to create a master list of listed properties situated in London. The task is to extract and blend property datasets across the Greater London area (United Kingdom) in one dataset.

## Property sites: 
Rightmove, Zoopla and On The Market (OTM)

## Required fields
<ul>
  <li>Transaction type (i.e. sale vs. rent - string)</li>
  <li>Bathrooms (integer)</li>
  <li>Bedrooms (integer)</li>
  <li>Description (free text string)</li>
  <li>Property type e.g. flat, detached house, terraced house</li>
  <li>Price e.g. 500,000 (typically integer)</li>
  <li>Location</li>
  <li>Key location data here is Postcode district and/or Postcode</li>
  <li>Agent (advertising the property)</li>
  <li>Listing source</li>
  <li>Listing URL</li>
  <li>Other nice-to-have metadata.</li>
</ul>

## Geographical Location
Greater London

## Process
<li>Extract/ scrape the datasets from all the above websites for a given day of your choosing.</li>
<li>Blend these data sets together into one dataset with unique records.</li>
