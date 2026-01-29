# Hubspot API & MCP Sandbox
This is an API sandbox for the Hubspot API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## Capability-Driven
This sandbox is capability-driven, using an early [prototype of the Naftiko capability schema as the manifest](capability-hubspot-sandbox.yml). The manifest provides the mapping to the OpenAPI source for the sandbox and guides the evolution of the sandbox, aligning with business outcomes—something we will keep iterating upon.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Hubspot API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Hubspot API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Hubspot API & MCP Sandbox.

- Number of Paths: 96
- Number of Operations: 133
- Number of Read Operations: 44
- Number of Write Operations: 89
- Number of Schemas: 241
- Number of Responses: 6
- Number of Parameters: 58
- Number of Examples: 148
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Hubspot API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Hubspot Analytics Events Api](openapi/hubspot-analytics-events-api-openapi.yml)
  - [Hubspot Blog Authors Api](openapi/hubspot-authors-api-openapi.yml)
  - [Hubspot Blog Posts Api](openapi/hubspot-blog-posts-api-openapi.yml)
  - [Hubspot Commerce Payments Api](openapi/hubspot-commerce-payments-api-openapi.yml)
  - [Hubspot Conversations Api](openapi/hubspot-conversations-api-openapi.yml)
  - [Hubspot Crm Associations Api](openapi/hubspot-crm-associations-api-openapi.yml)
  - [Hubspot Crm Feature Flags Api](openapi/hubspot-crm-feature-flags-api-openapi.yml)
  - [Hubspot Custom Workflow Actions Api](openapi/hubspot-custom-workflow-actions-api-openapi.yml)
  - [Hubspot Cms Domains Api](openapi/hubspot-domains-api-openapi.yml)
  - [Hubspot Crm Engagement Calls Api](openapi/hubspot-engagement-calls-api-openapi.yml)
  - [Hubspot Crm Engagement Notes Api](openapi/hubspot-engagement-notes-openapi.yml)
  - [Hubspot Marketing Transactional Email Api](openapi/hubspot-marketing-emal-api-openapi.yml)
  - [Hubspot Oauth Api](openapi/hubspot-oauth-api-openapi.yml)
  - [Hubspot Cms Source Code Api](openapi/hubspot-source-code-api-openapi.yml)

## Resources
These are the resources available via the Hubspot API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Access Tokens
  - Action Definitions
  - Action Functions
  - Actors
  - Application Feature Flags
  - Association Label Management
  - Association Type Definitions
  - Basic Operations
  - Batch Association Operations
  - Batch Operations
  - Batch Portal Operations
  - Blog Authors
  - Blog Posts
  - Channels
  - Definition Revisions
  - Domain Management
  - Drafts And Revisions
  - Event Instances
  - Event Types
  - File Content
  - File Extraction
  - File Metadata
  - File Validation
  - Gdpr Compliance
  - Inboxes
  - Messages
  - Multi-language Management
  - Object Associations
  - Payment Search
  - Portal Flag States
  - Post Cloning
  - Publishing And Scheduling
  - Refresh Tokens
  - Search
  - Single Payment Operations
  - Single Send
  - Smtp Token Management
  - Threads
  - Token Management
  - Workflow Callbacks

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Hubspot API & MCP Sandbox.

  - Archive A Thread
  - Archive Multiple Blog Authors
  - Archive Multiple Blog Posts
  - Archive A Blog Author
  - Archive A Blog Post
  - Archive A Batch Of Calls
  - Archive A Batch Of Commerce Payments
  - Archive A Batch Of Notes
  - Archive A Call
  - Archive A Commerce Payment
  - Archive A Note
  - Archive An Action Definition
  - Attach Author To Language Group
  - Attach Post To Language Group
  - Batch Archive Associations
  - Batch Create Associations
  - Batch Create Or Update Portal Flag States
  - Batch Delete Portal Flag States
  - Batch Read Associations For Multiple Objects
  - Clone A Blog Post
  - Complete A Single Callback
  - Complete Multiple Callbacks
  - Create Language Variation
  - Create Language Variation
  - Create Multiple Blog Authors
  - Create Multiple Blog Posts
  - Create A Blog Author
  - Create A Blog Post
  - Create A Batch Of Calls
  - Create A Batch Of Commerce Payments
  - Create A Batch Of Notes
  - Create A Call
  - Create A Commerce Payment
  - Create A New Source Code File
  - Create A Note
  - Create An Smtp Token
  - Create An Action Definition
  - Create An Association Between Objects
  - Create An Association Label
  - Create Or Refresh An Access Token
  - Create Or Update A Feature Flag
  - Create Or Update A Function
  - Create Or Update A Source Code File
  - Delete A Feature Flag
  - Delete A Function By Type
  - Delete A Portal Flag State
  - Delete A Source Code File
  - Delete A Specific Function
  - Delete An Smtp Token
  - Delete An Association Between Objects
  - Delete An Association Label
  - Detach Author From Language Group
  - Detach Post From Language Group
  - Download A Source Code File
  - Extract A Zip Archive
  - Get Revision History
  - Get A Call By Id
  - Get A Domain By Id
  - Get A Note By Id
  - Get An Smtp Token By Id
  - Get Extraction Task Status
  - List Actors
  - List All Blog Authors
  - List All Blog Posts
  - List All Inboxes
  - List Channels
  - List Conversation Threads
  - List Thread Messages
  - List Action Definitions
  - List Action Functions
  - List All Smtp Tokens
  - List All Association Definitions
  - List All Calls
  - List All Domains
  - List All Notes
  - List Association Labels
  - List Associations For An Object
  - List Commerce Payments
  - List Definition Revisions
  - List Portal Flag States
  - Permanently Delete A Call For Gdpr Compliance
  - Permanently Delete A Note For Gdpr Compliance
  - Push Draft To Live
  - Read Multiple Blog Authors
  - Read Multiple Blog Posts
  - Read A Batch Of Calls
  - Read A Batch Of Commerce Payments
  - Read A Batch Of Notes
  - Reset Draft To Live Version
  - Reset Smtp Token Password
  - Restore A Previous Version
  - Retrieve A Message
  - Retrieve A Thread
  - Retrieve An Actor
  - Retrieve An Inbox
  - Retrieve Available Event Types
  - Retrieve Event Instances
  - Retrieve A Blog Author
  - Retrieve A Blog Post
  - Retrieve A Commerce Payment
  - Retrieve A Feature Flag Configuration
  - Retrieve A Portal Flag State
  - Retrieve A Specific Function
  - Retrieve A Specific Revision
  - Retrieve Access Token Metadata
  - Retrieve An Action Definition
  - Retrieve File Or Folder Metadata
  - Retrieve Function By Type
  - Retrieve Refresh Token Metadata
  - Revoke A Refresh Token
  - Schedule A Blog Post
  - Search Calls
  - Search Commerce Payments
  - Search Notes
  - Send A Message
  - Send A Transactional Email
  - Set New Primary Language
  - Set New Primary Language
  - Set A Portal Flag State
  - Update A Thread
  - Update Multiple Blog Authors
  - Update Multiple Blog Posts
  - Update A Blog Author
  - Update A Blog Post
  - Update A Batch Of Calls
  - Update A Batch Of Commerce Payments
  - Update A Batch Of Notes
  - Update A Call
  - Update A Commerce Payment
  - Update A Note
  - Update An Action Definition
  - Update An Association Label
  - Validate A Source Code File

## Backstage
We provide a Backstage software catalog entity for the Hubspot API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Hubspot Analytics Events API](backstage/hubspot-analytics-events-api-api-sandbox-backstage.yml)
  - [Hubspot Blog Authors API](backstage/hubspot-authors-api-api-sandbox-backstage.yml)
  - [Hubspot Blog Posts API](backstage/hubspot-blog-posts-api-api-sandbox-backstage.yml)
  - [Hubspot Commerce Payments API](backstage/hubspot-commerce-payments-api-api-sandbox-backstage.yml)
  - [Hubspot Conversations API](backstage/hubspot-conversations-api-api-sandbox-backstage.yml)
  - [Hubspot Crm Associations API](backstage/hubspot-crm-associations-api-api-sandbox-backstage.yml)
  - [Hubspot Crm Feature Flags API](backstage/hubspot-crm-feature-flags-api-api-sandbox-backstage.yml)
  - [Hubspot Custom Workflow Actions API](backstage/hubspot-custom-workflow-actions-api-api-sandbox-backstage.yml)
  - [Hubspot Cms Domains API](backstage/hubspot-domains-api-api-sandbox-backstage.yml)
  - [Hubspot Crm Engagement Calls API](backstage/hubspot-engagement-calls-api-api-sandbox-backstage.yml)
  - [Hubspot Crm Engagement Notes API](backstage/hubspot-engagement-notes-api-sandbox-backstage.yml)
  - [Hubspot Marketing Transactional Email API](backstage/hubspot-marketing-emal-api-api-sandbox-backstage.yml)
  - [Hubspot Oauth API](backstage/hubspot-oauth-api-api-sandbox-backstage.yml)
  - [Hubspot Cms Source Code API](backstage/hubspot-source-code-api-api-sandbox-backstage.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Hubspot API & MCP Sandbox.

