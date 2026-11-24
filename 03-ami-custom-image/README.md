# 03 - Amazon Machine Image (AMI)

**Status:** Completed

## Project Overview

I created an Amazon Machine Image (AMI) from an existing EC2 instance. The goal was to understand how an existing server configuration can be captured and reused to launch additional EC2 instances with the same base configuration.

## AWS Services & Technologies

- Amazon EC2
- Amazon Machine Images (AMI)
- Amazon Linux
- Apache HTTP Server
- EC2 instance imaging

## What I Did

- Used an existing EC2 web server as the source instance.
- Started the process of creating a custom AMI from that instance.
- Verified the source EC2 instance was running and healthy.
- Practiced the workflow used to preserve and reuse a configured server image.

## Why AMIs Matter

An AMI provides the software and configuration needed to launch EC2 instances. Creating a custom AMI makes it possible to reproduce a known server configuration instead of rebuilding the system manually each time.

## Skills Demonstrated

- EC2 administration
- Server imaging
- Repeatable cloud deployments
- Infrastructure standardization
- AWS resource management

## Evidence

The screenshots show the running source EC2 instance and the AWS console confirming that a new AMI was being created.

## What I Learned

This project showed me how cloud images can support faster deployment, consistency, recovery, and scaling by allowing the same server configuration to be launched again when needed.
