# rancher-asg-host-lifecycle

A simple SQS processor to unregister hosts with Rancher on autoscaling event.

This code base has a modification from the original to respond to events based on instance id vs token. 

The dockerhub image, and usage instructions, are here: https://hub.docker.com/r/redaptcloud/rancher-asg-host-lifecycle/

## Credits

This is a copy and paste fork of the original handler by Tom Hill <tom@greensheep.io> as seen here: https://hub.docker.com/r/greensheep/rancher-delete-host
Original Github Repo, before re-name: https://github.com/eploko/rancher-asg-host-unregisterer