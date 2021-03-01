# Docker image containing Antora and the tools used to generate the doc

## Build the image

```
docker build -t lightbend/antora-doc:<version> .
```

## Publish the image

Login as `lightbend` on docker. Credentials available in keybase.

```
docker push lightbend/antora-doc:<version>
```

Note: Only contributors with access to the Lightbend credentials are able to publish this image.
