# samsch.org

Personal website and public pages.

Deployment is expected to be handled by a gitignored `deploy` executable file/script.

This script should copy/overwrite from the generated `public` folder to the server `public` folder.

One way to do this is with rsync, like `rsync -avz --del public/ <ssh shortcut name, or user@host>:/path-to/public/`.

## hexo stuff

This whole thing is built with Hexo

```
# local dev
npm run hexo -- server

# build
npm run hexo -- generate
```

The generated files *are* committed. I don't necessarily remember why originally, but it's helpful to have an exact record of the files on the website, so that's why I'm keeping it.
