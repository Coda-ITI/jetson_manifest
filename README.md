# jetson_manifest

To initialize the working dir simply :

```bash
repo init -u https://github.com/Coda-ITI/jetson_manifest.git -b main
repo sync
```

this will fetch the relevant layers and add them alongside the conf for the jetson nano to the local.conf

since the build dir setup is done through repo hooks you will need to allow repo to excute the post-sync script [you can find the script here](https://github.com/Coda-ITI/jetson-hooks)
