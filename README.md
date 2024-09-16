# Hello world docker action

This action uses Tailcall Launchpad Service to deploy a GitHub repository that contains
a Tailcall configuration in the cloud.

## Inputs

## `LAUNCHPAD_URL`

**Required** The URL of the hosted Tailcall Launchpad Service (used for development purposes).

## Outputs

## `DEPLOY_URL`

The URL of the deployed service.

## Example usage

```yaml
uses: karatakis/launchpad-action@v1
with:
  LAUNCHPAD_URL: launchpad.tailcall.run
```