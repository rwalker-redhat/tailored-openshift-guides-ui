For use with https://github.com/rwalker-redhat/tailored-openshift-guides


Tweak and manually zip up the contents, so contents is in the root of the archive. Copy the zip file into root of the project and update `site.yml` & `dev-site.yml` to point at that archive.

For example:

```
ui:
  bundle:
    url: ui-bundle.zip
```