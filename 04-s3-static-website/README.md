# 04 - Amazon S3 Static Website

**Status:** Completed

## Project Overview

I created an Amazon S3 bucket, uploaded an HTML file, configured the bucket for static website hosting, and tested the resulting site in a web browser.

## AWS Services & Technologies

- Amazon S3
- S3 buckets and objects
- Bucket permissions
- Bucket policy concepts
- Static website hosting
- HTML

## What I Built

I uploaded an `index.html` file to an S3 bucket and configured the bucket so the page could be served as a static website.

## Validation

I confirmed that:

- The HTML file uploaded successfully.
- The object appeared in the S3 bucket.
- The static website endpoint was reachable.
- The browser displayed the expected **Hello World!** page.

## Skills Demonstrated

- AWS object storage
- S3 bucket creation
- Object uploads
- Static website hosting
- Access and permissions concepts
- Deployment validation

## Security Considerations

This lab required public access so the static website could be tested. In a production environment, public access should be enabled only when required and configured as narrowly as possible.

## Screenshots

Screenshots show the successful upload of `index.html` and the working S3-hosted static website.

## What I Learned

This project helped me understand how S3 can be used for more than file storage. It can also serve static web content while using bucket-level access controls and policies to control availability.
