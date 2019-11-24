# Website for Codesys Oy

Live: https://www.codesys.fi

## Requirements

GCP SDK: https://cloud.google.com/sdk/

## Config

GCP project ID is stored .env
This is required for the 'set-project' script to run.
See example in env.sample.

## Deployment

Preparations (when needed):
- `npm run login`
- `npm run set-project`

Deployment:
- `npm run deploy`