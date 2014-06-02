# Introduction

Steelmesh is an application delivery and hosting platform utilizing [CouchDB](http://apache.couchdb.org) and [nginx](http://nginx.org) for application distribution and content serving respectively.  The core principle of Steelmesh is that applications are uploaded into a CouchDB database is then synchronized with one or more servers that download the apps and run then, proxying each app through an nginx instance.
