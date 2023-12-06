# What?

This package is just types for the scaleway provider that we can use in typescript to allow us to make our infra as code work in typescript.

To make a new version run the command:

```bash
npm run get
```

This will download the latest version of the provider and generate the types for it via the cdktf library.

You can change the version in the cdktf.json file, if you want to update to use a new version of the provider. But we should maybe make the versions of this package then match the new version in scaleway provider.

So we know what version we are using. that is what I have already done so far.

Once you publish this package you can use it in other repos.
