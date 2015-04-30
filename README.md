# ez5-no-reg

Disables the registration component of eZ Community Edition 2014.07.

Forced registration is not something that belongs in an open source project.

## Usage

From the root install directory, before running the eZ Publish install wizard, run

```
patch -p2 < ezpublish5_community_project-2014.07.0-gpl-full-no_registration.patch
```
