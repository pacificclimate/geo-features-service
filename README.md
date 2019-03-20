# Geospatial Features Service

A web service providing geospatial features.

**NOTE: This is an early draft. It requires review and probably revision
before proceeding.**

This service provides a simple storage and retrieval service for
applications that want to have a collection of geospatial features
available for easy loading. 

Example clients: PCIC Climate Explorer, Plan2Adapt.

## Requirements

### Basics

1. RESTful API

### Minimum viable product

1. Resources: 
   1. features collection:
      1. managed by PCIC
1. Any client can:
   1. search/list features
   1. get details of a feature

### Minimum user-segregated product

1. Resources: 
   1. users collection: 
      1. managed by PCIC
      1. PCIC is a user
   1. features collection:
      1. segregated into collections per user 
      1. managed by users
      1. user can designate own feature as public or private
1. Any client can search/list or get details of:
   1. public features from any user
   1. their own (user) private features
1. Any user can create, delete, or update their own features.