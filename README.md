# Cygnus

> A friendly fork of https://github.com/TryGhost/Lyra aimed for a first class portals experience (context: https://github.com/TryGhost/Lyra/issues/206).

A paid-members publication for Ghost. Can be used with no code knowledge required.

# What's different

- Paid posts have a tag that show paid, not free
- We are using the built in portal, not the custom members experience

# Instructions

1. [Download this theme](https://github.com/gabrielcsapo/Cygnus/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file
3. Unzip the theme archive on your computer and locate the file called `routes.yaml`
4. Inside Ghost admin, go to the `Labs` settings area and scroll down until you see the `Custom Routes` section
5. Upload the `routes.yaml` from this theme

That's it! You now have a Ghost publication which supports free and paid memberships. If you need help, check out the <a href="https://ghost.org/docs/members/">Ghost members documentation</a> or chat with other Ghost users on <a href="https://forum.ghost.org">Ghost forum</a>.

![screenshot](https://user-images.githubusercontent.com/120485/67228748-1fdd1400-f464-11e9-921f-ecbf5f412ed5.png)

# Development

> Checkout https://www.chrisjmendez.com/2021/06/03/ghost-blog-theme-development/ for a great tutorial on how to do theme development

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```
