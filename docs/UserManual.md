# AAFC-DINA User Manual

## General Concepts

### Group

Groups are used to define set of users for administration purpose (mostly permissions). They usually align with collections.
A user can belong to more than 1 group.

Groups are also used to defined who owns an object. For example, an object in the object store always belongs to a group.
Objects can only have 1 owner.

### Role

Roles are specific to groups. A Collection Manager in Group A is not Collection Manager in Group B.

Current roles are:

* Administrator
* Collection Manager
* Staff
* Student

### Permissions

* Admins can do everything
* Read permission are given to all authenticated user
* For most of the objects, all members of a group will have Write permission for objects within that same group (Collecting-Event, Material Sample)
* For some objects, Write permission are only available to the Collection Manager role (Agent, Managed Attribute)

### User

Users (when enabled) can access the system. What a user can and cannot do is based on the group(s)/permission(s). When using an external Identity Provider (e.g. ESAS) the user account must be linked to the Identity Provider account. Once done, the user will be able to use a third-party authentication (e.g. ESAS) to access the system.

## Collection Component

### Collection

A Collection represents the top entity that can contain material-sample. Top collections (or parent collections) generally represent a natural history collection or a laboratory. A collection can contain multiple sub-collection(s).

## Agent Component

## Object-Store Component

## Identifiers

All object in DINA are identified with UUID (universally unique identifier). While this type of identifier is not considered human-readable (123e4567-e89b-12d3-a456-426614174000) it has the property to be virtually universally unique (chances of duplicates are close enough to zero to be considered negligible). Objects can be uniquely identifed even outside DINA the DINA system.
