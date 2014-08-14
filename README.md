household_objects_backups
=========================

Storage location (temporary?) for backup of files from https://code.ros.org/svn/data/trunk/household_objects/

It is suggested to use the latest full dump of the database when trying to get this to work with GraspIt!

Basic description of files in this repo:

schema of original release of hho database
```
  household_objects-0.2-schema.backup 
```
full dumps of releases of hho database
```
  household_objects-0.2.backup
  household_objects-0.4_diamondback_prerelease.backup
  household_objects-0.4_diamondback_prerelease_2.backup
  household_objects-0.5_electric_prerelease_1.backup
  household_objects-0.5_electric_prerelease_2.backup
  household_objects-0.5_electric_prerelease_3.backup
  household_objects-0.6_fuerte_prerelease_1.backup
  household_objects-0.7_groovy_prerelease_1.backup
```
  (note the 0.7 dump is a copy of the original experimental dump with experimental portions trimmed out.)

experimental dump of database
```
  household_objects-experimental.backup
```
  (note the optimization_tasks & view tables were truncated to fit within github size restrictions using it is not suggested. )
