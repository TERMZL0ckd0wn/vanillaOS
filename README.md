# Mxrkdv's vanillaOS Image

> [!TIP]
> It is suggested to check the [Vib documentation](https://docs.vanillaos.org/collections/vib) to know more about the recipe format, structure of modules and the supported fields.

## Features
- Tailscale is pre-bundled

## Use your custom image

If your image is successfully built, you can then point ABRoot to your custom image to use it.

- Edit the configuration file with the command: `abroot config-editor`.
- Change the "name" entry from something like `vanilla-os/desktop` to `your-github-name/your-image-name` (for example `taukakao/custom`).  [**Note**: All characters must be in lowercase.]
- Now, Run `abroot upgrade` to switch to your custom image.
