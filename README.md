# Turbo Pascal 7.0 binaries

The binaries are installed and patched from from https://winworldpc.com/download/e530a58d-6134-11ea-8c4a-fa163e9022f0. They are ready to run on your favourite DOS emulator.

![Screenshot](turbo_001.raw1.png?raw=true)

## Getting started

- Clone the repo
- Add the following to the `[autoexec]` section of your emulator's config file ([DOSBox](https://www.dosbox.com/wiki/Dosbox.conf), [DOSBox-X](https://dosbox-x.com/wiki/Home#_dosbox_xs_configuration_file)):

```
[autoexec]
MOUNT C: /Volumes/Tony/dosbox
PATH %PATH%;C:\TP\BIN
C:
```

- Start your emulator, and run `TURBO` at the prompt.
