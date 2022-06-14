# Starter Instruction

Using the CLI tool:

<https://developers.openfin.co/of-docs/docs/openfin-cli-tool>

To wrap the site `https://starter.openfin.solutions` and save the generated manifest as `manifest.fin.json`

```shell
npm install -g openfin-cli
openfin --launch --url https://starter.openfin.solutions --save manifest.fin.json
```

## Create installer

Assuming we have then hosted the `manifest.fin.json` in a location, such as
<https://starter.openfin.solutions/manifest.fin.json>

We can use the installer generator with the following tool:

<https://start.openfin.co/>

Or directly:

<https://start.openfin.co/?manifest=https%3A%2F%2Fstarter.openfin.solutions%2Fmanifest.fin.json>

## Notifications

Run an example showing how notifications are displayed:

<https://start.openfin.co/?manifest=https%3A%2F%2Fbuilt-on-openfin.github.io%2Fworkspace-starter%2Fworkspace%2Fv7.0.0%2Fuse-notifications%2Fmanifest.fin.json>

The code for the notifications.

<https://github.com/built-on-openfin/workspace-starter/blob/main/how-to/use-notifications/client/src/notifications.ts>