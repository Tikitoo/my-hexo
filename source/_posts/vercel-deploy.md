---
title: Vercel deploy hook
---


Deploy Hooks allow you to create URLs that accept HTTP requests in order to trigger deployments and re-run the Build Step. These URLs are uniquely linked to your project, repository, and branch, so there is no need to use any authentication mechanism or provide any payload to the request.POSTPOST

This feature allows you to integrate Vercel deployments with other systems. For example, you can set up:

Automatic deployments on content changes from a Headless CMS
Scheduled deployments by configuring third-party cron job services to trigger the Deploy Hook
Forced deployments from the command line