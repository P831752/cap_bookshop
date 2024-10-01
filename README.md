# Getting Started
Working Fine. Data is coming from HANA Cloud DB.
- npm install
- npm install -g hana-cli
- npm add @sap/cds-common-content –save

cds add hana

- cds build --production
- cds watch

BAS - SAP HANA Projects,
- Bind --> Bind to an HDI container --> new service instance
  and Deploy. Now check in HANA Database Explorer in BTP

Run the services
- cds bind -2 cap_bookshop-hdi-dev
- cds watch --profile hybrid
=========================================================



Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch`
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
