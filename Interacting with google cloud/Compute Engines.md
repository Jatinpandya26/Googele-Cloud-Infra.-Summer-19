# COMPUTE ENGINE
##Jatin pandya

* Compute Engines InstantAdmin Role Lets Whoever Has That Role Perform a Certain Set of Actions on Virtual Machines 
## Notes
## Actions

* The Actions Are: Listing them, Reading and Changing their Configurations, and Starting and Stopping them

* All the users of a certain Google Group have the role, and they have it on all the virtual machines in a project. 

* If you need something even finer-grained, there are custom roles. A lot of companies have a least-privileged model in which each person in your organization has the minimum amount of privilege needed to do his or her job.

* Custom Roles Can only be used at the project or organization levels. They can't be used at the folder level

## Service Accounts

* Service accounts are named with an email address. But instead of passwords, they use cryptographic keys to access resources.

* This would allow an application running in a VM with that service account.
