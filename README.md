# Smart India Hackathon Workshop
# Date: 13.05.24
## Register Number: 212223040114
## Name: MOHAN RAJ C
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
The increasing amount of electronic waste (e-waste) poses significant environmental and health hazards if not properly managed. However, many individuals and businesses struggle to locate nearby facilities equipped to handle e-waste disposal. Creating a centralized platform to locate these facilities could streamline the process of responsibly disposing of electronic devices.

## Proposed Solution / Architecture Diagram


![328744386-6d73b151-6ff0-407d-af2d-d3bb53776120](https://github.com/Mohanraj2006/SIHPS/assets/152195759/cbb51846-7a8b-44ce-a787-646ab151902a)

Develop a web or mobile application that allows users to easily locate nearby e-waste recycling facilities based on their current location or specified area. The application would provide information such as facility addresses, contact details, operating hours, accepted items, and any specific instructions for disposal. Users could also rate and review facilities based on their experiences, helping others make informed decisions.

## Use Cases

![329215163-0c5bbdc2-8d79-411a-96ac-c5dccbd551aa](https://github.com/Mohanraj2006/SIHPS/assets/152195759/8a7c306a-9503-4411-96d1-bcceca34b4bd)


1. Individuals: People looking to dispose of old electronic devices such as smartphones, laptops, or TVs can use the app to find the nearest recycling center.

2. Businesses: Companies seeking to responsibly dispose of bulk e-waste from outdated equipment or office electronics can locate appropriate facilities for proper recycling or disposal.

3. Government Agencies: Municipalities or environmental organizations can use the platform to promote e-waste recycling initiatives and encourage citizen participation.

4. Educational Institutions: Schools and universities can educate students and staff about the importance of e-waste recycling and provide them with a tool to locate nearby facilities.

## Technology Stack
Frontend: React.js for web or React Native for mobile application development.

Backend: Node.js with Express.js for RESTful API development.

Database: MongoDB for storing facility information, user data, and reviews.

Geolocation Services: Integration with Google Maps API or OpenStreetMap for location-based search and mapping functionalities.

Authentication: JSON Web Tokens (JWT) for user authentication and authorization.

Deployment: Docker for containerization and deployment on cloud platforms like AWS or Heroku.

Version Control: Git for code management and collaboration.

## Dependencies
Data Sources: Access to a reliable database or API containing information about e-waste recycling facilities worldwide.

Mapping Services: Integration with mapping services to display facility locations and provide directions.

User Reviews: Implementing a review system would require mechanisms for users to submit and display reviews, as well as moderation features to manage content.

Legal Compliance: Ensuring compliance with local regulations regarding e-waste recycling and data privacy laws.

Maintenance: Regular updates and maintenance to keep the database of facilities current and accurate.
