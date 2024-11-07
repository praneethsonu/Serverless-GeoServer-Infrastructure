# Serverless GeoServer Infrastructure with PostgreSQL and PostGIS Integration

## Description:
Deploy and auto-scale GeoServer with PostgreSQL and the PostGIS extension on AWS. This project leverages containerized deployment using AWS Fargate, enabling you to focus on geospatial data management without the complexities of server maintenance.

## Architecture Overview:
At the completion of this lab you will have created an autoscaling Fargate service hosting GeoServer containers. This provides a highly available load balanced architecture without the overhead of having to manage your own servers or load balancing infrastructure. Supporting this is a highly available shared file system for the GeoServer configuration and data directory. We also provide a highly available PostgreSQL PostGIS database as a geospatial data source.
![GeoserverArchitecture](https://github.com/user-attachments/assets/70838ab8-e409-4164-bf24-5a40ab20c256)
