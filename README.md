# Quobyte Dashboards 

Collection of Grafana Dashboards build on Quobyte metrics.

## The generic Quobyte Dashboard 

Quobyte Dashboard.json

will provide a generic overiew and is considered a good starting point. 
This dashboard is also available via https://grafana.com/grafana/dashboards/14496-quobyte-dashboard-3-x/

## Performance Dashboard

[WIP] - Performance Dashboard.json

A work in progress dashboard that covers important performance metrics.
You can use it to do proper resource analysis/ planning; for example
metadata heap sizing.

## Availability Dashboard

Storage availability.json

This dashboard gives you a condensed view on core components and their 
current status.
First row covers general cluster resources, mostly the registry database.
You can see if somthing is blocked or fail overs happening there.

Second row goes mostly into the metadata system:
Are all volumes accessible, i.e. served by a working metadata service?

Last chapter covers core aspects of the client view.
