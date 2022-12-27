# AWS-Kibana

This repository contains a simple Cloudformation template to create a standalone Kibana service
in AWS. (i.e. Elasticsearch and Logstash are not included)

Google auth is used to secure the service. As such, you'll need to
create a Google Cloud project with access to the Google+ API, and to
generate access credentials from this.

Note: It is assumed that you are running an existing Elasticsearch cluster
with data on it to point Kibana at.