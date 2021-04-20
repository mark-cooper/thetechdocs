---
layout: default
title: Backend (REST API)
nav_order: 1
has_children: false
permalink: /docs/technical-overview/architecture/backend
parent: Architecture
grand_parent: Technical overview
---

# The ArchivesSpace Backend (REST API)

The backend is responsible for implementing the ArchivesSpace API, and supports
the sort of access patterns shown in the previous section. We’ve seen that the
backend must support CRUD operations against a number of different record types,
and those records as expressed as JSON documents produced from instances of
JSONModel classes.
