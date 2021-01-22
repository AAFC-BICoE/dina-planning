# AAFC-DINA User Manual

## Groups

In DINA, groups are used to define a set of users. Mainly a natural history collection or a laboratory.
A user can belong to more than 1 group.

Groups are also used to defined who owns an object. For example, an object in the object store always belongs to a group.
Objects can only have 1 owner.


## Roles

Roles are specific to groups. A Collection Manager in Group A is not Collection Manager in Group B.

Current roles are:

* Administrator
* Collection Manager
* Staff
* Student

## Permissions

* Admins can do everything
* Read permission are given to all authenticated user
* For most of the objects, all members of a group will have Write permission for objects within that same group
* For some objects, Write permission are only available to the Collection Manager role

## Identifiers

All object in DINA are identified with UUID (universally unique identifier). While this type of identifier is not considered human-readable (123e4567-e89b-12d3-a456-426614174000) it has the property to be virtually universally unique (chances of duplicates are close enough to zero to be considered negligible). Objects can be uniquely identifed even outside DINA the DINA system.
