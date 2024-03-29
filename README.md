# chrome-apps-cookiecutter
Cookiecutter template to making simple Google Chrome apps

> Google deprecated Chrome Apps on December, 2022 in favour of progressive web apps (PWAs).
>
> This repository has been archived and is no longer maintained.

### Usage

Requires `cookiecutter` installed on your system.

```
pip install cookiecutter --user
```

Then, simply run the following command:

```
cookiecutter https://github.com/epassaro/chrome-apps-cookiecutter
```

Finally, open `chrome://extensions` on your browser, activate _Developer mode_ and load the unpacked extension. Go to `chrome://apps`, right click on your application and select _Open as window_ and _Create shortcuts_.

### Icons

`cookiecutter` will ask you for the URL of a PNG icon with size of 128x128 px. To choose a local file instead use `file://path/to/file.png`.


## References

- [Create and publish custom Chrome apps & extensions](https://support.google.com/chrome/a/answer/2714278?hl=en)
