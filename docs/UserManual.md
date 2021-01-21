# AAFC-DINA User Manual

## Groups

In DINA, groups are used to define a set of user. Mainly a natural history collection or a lab.
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
