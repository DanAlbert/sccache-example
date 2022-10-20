# NDK sccache example

This sample shows how to use [sccache](https://github.com/mozilla/sccache) with
externalNativeBuild. It works, but isn't really complete. Still TODO to make it
actually useful:

- [ ] Use a GCS bucket to cache results between workflow runs
- [ ] Build a docker image or something for the builder so installing sccache
      from cargo isn't the dominant build step.
