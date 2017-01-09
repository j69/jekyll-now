---
layout: post
title: Users roles
date: 2016-01-09
---

First of all, what type of security model do you plan to implement? Role-based Access Control (RBAC) or Discretionary Access Control (DAC)?

RBAC in the Role-Based Access Control (RBAC) model, access to resources is based on the role assigned to a user. In this model, an administrator assigns a user to a role that has certain predetermined right and privileges. Because of the user's association with the role, the user can access certain resources and perform specific tasks. RBAC is also known as Non-Discretionary Access Control. The roles assigned to users are centrally administered.

DAC In the Discretionary Access Control (DAC) model, access to resources is based on user's identity. A user is granted permissions to a resource by being placed on an access control list (ACL) associated with resource. An entry on a resource's ACL is known as an Access Control Entry (ACE). When a user (or group) is the owner of an object in the DAC model, the user can grant permission to other users and groups. The DAC model is based on resource ownership.

For sites its usually
Users -> Roles

or simple use `is_admin` column in Users table 