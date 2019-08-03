# automate-sproc
Fixes Connectwise Automate SPROC error

There's a bug in one of the Labtech/Automate stored procedures:  sp_AutoRemoveComputersMasterTrump

Running the following query in MySQL or MariaDB will fix it.  This is for version 12.0.12. (Q2 2019)
