Tool agnostic information flow - common information/data that is being used at each stage of the inspections.

This table can be used in conjunction with the [Tooling Comparison](Tooling-comparison) table. This table looks at the data flowing in and out through the stages of inspection. The format is similiar to the tooling comparison table: the stages of inspection and jobs to be done follow are the same. At each stage and job level the data coming in is presented in a tool agnostic way. That is, the commonalities that are across all inspection services are shown without their respective tools. This could be used when planning development work in order to keep an eye on scability of a service.

| **Stage of inspection** | **Job to be done**              | **Data used (all)**                                                    |
|---------------------|-----------------------------|--------------------------------------------------------------------|
| **Planning**            |                             |                                                                    |
|                     | ***Trigger to inspect***          | Email checking                                                     |
|                     |                             | Excel/spreadsheet monitoring for outstanding visits                |
|                     |                             | Next visit due                                                     |
|                     |                             | RAG/traffic light system monitoring                                |
|                     |                             | Postcodes - for locale/area/cluster                                |
|                     |                             | FBO ID numbers                                                     |
|                     |                             | Compliance reports                                                 |
|                     |                             | Enforcement history                                                |
|                     |                             | Reports                                                            |
|                     |                             | Previous visit reports                                             |
|                     |                             | Health and safety rating                                           |
| **Schedule**            |                             |                                                                    |
|                     | ***Assigning***                   | Assign a visit to self/inspector using system                      |
|                     |                             | Add to calendar                                                    |
|                     | ***Nearby FBOs***                 | Area/Cluster/Locale checking other nearby FBOs                     |
|                     | ***Route planning***              | Postcode(s)                                                        |
|                     |                             | Mapping software                                                   |
|                     |                             |                                                                    |
| **Prepare**             |                             | Broadly all these items are scraped in from other sources          |
|                     | ***Plant profiles***              | Cheat sheet template                                               |
|                     |                             | Previous inspection reports                                        |
|                     |                             | Health and Safety score                                            |
|                     | ***Business info***               | Contact names                                                      |
|                     | ***Business info***               | Phone numbers                                                      |
|                     | ***Business info***               | Business address                                                   |
|                     | ***Business info***               | Contact address                                                    |
|                     | ***Business info***               | Limited company information                                        |
|                     |                             | Audit reports                                                      |
|                     | ***Enforcement history***         | Open/outstanding infractions                                       |
|                     |                             | Health and safety rating                                           |
|                     | ***Past reports - photos***       | Photos                                                             |
| **Inspect**             |                             |                                                                    |
|                     | ***Tools to inspect***            | FSA notebook                                                       |
|                     |                             | Inspector name                                                     |
|                     |                             | Date                                                               |
|                     |                             | Signature                                                          |
|                     |                             | Infringement                                                       |
|                     |                             | Aide memoire - memory jog of open ionfractions and standard checks |
|                     | ***Evidence gathering***          | Health and safety notes                                            |
|                     |                             | Who was met                                                        |
|                     |                             | Sampling apparatus                                                 |
|                     |                             | Inspection form(s) - either made up ad-hoc or official template    |
|                     |                             | Legislation cheatsheet                                             |
|                     | ***Evidence gathering - photos*** | Photo                                                              |
|                     |                             | Photo timestamp                                                    |
|                     |                             | Photo geolocation                                                  |
| **Report**              |                             |                                                                    |
|                     | ***Write-up*** ***                   | Infringements                                                      |
|                     |                             | FBO business information if changed                                |
|                     |                             | Updating spreadsheet with findings                                 |
|                     |                             | Updating operations spreadsheet                                    |
|                     |                             | Letter templates                                                   |
|                     |                             | Letters                                                            |
|                     |                             | Email to CSU                                                       |