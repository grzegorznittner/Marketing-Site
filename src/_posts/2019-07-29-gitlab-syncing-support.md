---
title: GitLab syncing support
author: mike
category: Features
image: /uploads/cover.jpg
image_featured: true
---

We've seen GitLab grow from a self hosted alternative to GitHub to an entire suite of tools to build and deploy software used by some of the largest companies in the world. GitLab support is one of our most hotly requested features for CloudCannon. Today we're happy to announce CloudCannon now has full GitLab.com integration\!

## How does it work?

First create a new site on CloudCannon and select the GitLab Repository button.<br><br>![Connect GitLab Repository](/images/blog/gitlab-support/2@2x.png){: .screenshot srcset="/images/blog/gitlab-support/2.png 800w, /images/blog/gitlab-support/2@2x.png 1600w"}

If it's your first time connecting a GitLab repository you will need to authenticate. After authenticating, CloudCannon shows a list of your repositories. Select your desired repository and branch.<br><br>![Select Repository](/images/blog/gitlab-support/1@2x.png){: .screenshot srcset="/images/blog/gitlab-support/1.png 800w, /images/blog/gitlab-support/1@2x.png 1600w"}

CloudCannon syncs the files from your repository, builds the Jekyll site and serves it live. Updates made on CloudCannon sync back to the GitLab repository and vice-versa for changes made to the GitLab repository. Branching and publishing workflows are fully supported with this integration too.<br><br>![Live Site](/images/blog/gitlab-support/3@2x.png){: .screenshot srcset="/images/blog/gitlab-support/3.png 800w, /images/blog/gitlab-support/3@2x.png 1600w"}

## Wrap up

We're always looking for ways to help developers work with their favourite tools and platforms. Let us know if there's something we can add for your workflow.