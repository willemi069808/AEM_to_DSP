# Walkthrough: Capturing Business Events in SAP Datasphere using SAP Integration Suite

This repository is part of a [SAP Blog](https://blogs.sap.com/2023/05/15/walkthrough-capturing-business-events-in-sap-datasphere-using-sap-integration-suite/). The blog explores how to connect Advanced Event Mesh with SAP Datasphere.

## Content
In this repository you will find:
- in [/Datasphere](./blob/main/Datasphere/):
    - Sample SQL statements to create database tables
- in [/Cloud Integration](./blob/main/Cloud%20Integration/):
    - The pre-built integration package to be imported in your integration tenant
    - CloudEventsSchema.xsd to be used in the XML Validator step
    - Mapping XSD schemas to be used in the Message Mapping steps
- in [/Sample data](./blob/main/Sample%20data/):
    - Sample JSON event payloads you can send via the HTTP endpoint or via the event broker

## Using the prebuilt integration package
1. Import the ZIP file
2. Create the security credentials as mentioned in the blog
3. Open the integration package, and click on the Actions button next to the "Event_Processor" integration flow, and choose "Configure" to change the configuration
4. Use the Actions button of each artifact to Deploy (activate) them
5. Refer to the Testing section in the blog for testing
