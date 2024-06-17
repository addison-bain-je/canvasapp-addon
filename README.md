# Introduction 
Canvas App Add-On (with Sharepoint) to address Power Apps license limitation for Model-Driven app (Dataverse)

# Data Sync

Set up 3 automated flows to sync from Dataverse to SharePoint List, whenever any of these change happens to a particular record in Dataverse
- New
- Change
- Delete

For flow to write-back from Canvas App to SP List, and then to Dataverse table
- Include a field for SharePoint sync flag (when list item is modified from canvas app only)

All flows are operated thorugh a single Service Account (with premium license), to avoid licensing need for all other app users

