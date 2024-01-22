
  ![AREA](arrea.jpeg)
## Introduction
The purpose of this document is to explain how to use the different
functionalities of the AREA application.
This guide is designed for both the web and the mobile version of the
application.
Through this document you will learn how to properly use AREA.

## Register & Login.

### Register to AREA.

The user management module involves the registration process.
Unidentified users register via an online mini-form, and the application server validates the account creation stage.
To create your account, you need an email address and a password. The username is deducted from the e-mail address.
This information can be modified later in the application.

### Login to AREA.

Users can authenticate via a username/password.

## Application overview.

Here are the different pages that you can find in AREA:

- Login page 
- Registration page
- Actions/Reactions page
- Services page 
- Actions/Reactions creation page
- Profile page

## AREA page

This is an application page dedicated to displaying information about "AREA". 

## Services page.

This page focuses on the presentation and management of the services provided by the application. It contains details of the features available, as well as service offers related to the application's functionality.

## Create a new AREA.

You can create an AREA from services.
Each service has a list of predefined actions and reactions. 
predefined reactions. AREAs are therefore created by and there are many possible combinations.
To do this, you need to select a trigger and then a reaction.

## Profile page.

This page is about user profiles. Users can have individual profiles where they can view and manage their  personal information, settings or preferences.
Using the corresponding form, you can edit your personal information, this include: your username and your
password.

## Edit an existing AREA.

This action consists of modifying or updating the details of an existing AREA. 

## Delete an existing AREA

This action removes or deletes an existing domain from the system. This is an important operation, and users generally require appropriate authorization to perform this action to avoid accidental deletions.

## Service Subscription.

Users subscribe to services from their services page.

## Triggers overview.

Each service may offer Action components that activate triggers based on conditions. Examples include new messages, file additions, or time-based triggers.

## Reactions overview.

Services may offer Reaction components, which perform specific tasks when triggered. Examples include posting messages, adding files, or sending messages.

## AREA: Action Reaction Execution

After subscribing to services, users can create AREA to execute a Reaction when an Action is detected. Examples include triggering a Reaction when receiving an email with an attachment.

## Docker Compose Setup

A docker-compose.yml file at the root of the project describes different Docker services. It includes:

  - server: Launches the application server on port 8080.
  - client_mobile: Builds the mobile client apk.
  - client_web: Launches the web client on port 8081.

The web client depends on both the mobile client and the server.