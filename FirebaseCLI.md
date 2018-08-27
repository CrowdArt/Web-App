sudo  npm install -g firebase-tools
Password:
/usr/local/bin/firebase -> /usr/local/lib/node_modules/firebase-tools/bin/firebase

> @google-cloud/functions-emulator@1.0.0-beta.5 postinstall /usr/local/lib/node_modules/firebase-tools/node_modules/@google-cloud/functions-emulator
> node scripts/upgrade-warning


If you're using the Emulator via the Firebase CLI, you can
disregard this message.

If you're upgrading @google-cloud/functions-emulator, these
are the recommended upgrade steps:

1.  Stop the currently running emulator, if any:

        functions stop

2.  Uninstall the current emulator, if any:

        npm uninstall -g @google-cloud/functions-emulator

3.  Install the new version of the emulator:

        npm install -g @google-cloud/functions-emulator

If you have trouble after upgrading, try deleting the config
directory found in:

    ~/.config/configstore/@google-cloud/functions-emulator

Then restart the emulator. You can also check for any renegade
Node.js emulator processes that may need to be killed:

    ps aux | grep node
