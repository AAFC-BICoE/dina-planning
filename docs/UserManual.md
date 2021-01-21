# AAFC-DINA User Manual

## Groups

In DINA, groups are used to define a group of user. Mainly a natural history collection or a lab.
A user can belong to more than 1 group.

Groups are also used to defined who own an object. For example, an object in the object store always belong to a group.
Objects can only have 1 owner.


## Roles

Roles are specific to groups. A Collection Manager in Group A is not Collection Manager in Group B.

Current roles are:

* Administrator
* Collection Manager
* Staff
* Student

## Permissions

* Admin can do everything
* Read permission to all authenticated user
* For most of the objects, Write permission to all members of a group for objects within that same group
* For some objects, Write permission to Collection Manager only
