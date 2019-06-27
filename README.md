# D365FO-Extensions
Microsoft Dynamics 365 for Finance and Operations - small &amp; useful extensions

This repository contains useful extensions for Dynamics 365 for Finance and Operations.

Source code of each tool/extension is under separated folders/models in master branch and the deployable packages are provided under 'Release' folder of the master branch.

# DMF Recurring file download
DMFRFD: This tool/extension makes possible to view and download the message(s) which was sent to Inbound Recurring Integration Queue (even it's failed or processed).

Relates to this topic:
https://experience.dynamics.com/ideas/idea/?ideaid=7e1d40c7-7c41-e711-80c0-00155d7cb38d

# DMF Staging CleanUp periodic function
DMFCS: This periodic function helps to clean up and keep tidy the data management staging tables. It offers possibility to:
- schedule the clean up in batch periodically
- filtering available based on the days passed since execution of the import/export 
- data project filtering also available
- class (function) can be used on manually created batch tasks too

Additionally package contains a form to help to identify the number of records in various used staging tables (be aware this form could load for a while because of the calculation running in the background). 

Both the service and the form can be found under System administration \ Periodic \ Data management as 'Staging CleanUp service' and 'Staging CleanUp scheduler'.

Relates to this topic:
https://experience.dynamics.com/ideas/idea/?ideaid=54dc867d-7a31-e811-bbd3-0003ff68ba15

# DISCLAIMER

Sample scripts in this repository are not supported under any kind of support program or service. The sample scripts are provided AS IS without warranty of any kind. The repository owner disclaims all implied warranties including, without limitation, any implied warranties of merchantability or of fitness for a particular purpose. The entire risk arising out of the use or performance of the sample scripts and documentation remains with you. In no event shall the repository owner, the authors, or anyone else involved in the creation, production, or delivery of the scripts be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or inability to use the sample scripts or documentation, even if the repository owner or the authors have been advised of the possibility of such damages.

