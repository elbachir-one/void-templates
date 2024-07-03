# Void Templates

These are some additional Void Linux templates that are not included in
the official void-packages repository.

To use these templates:

```bash 
git clone https://github.com/void-linux/void-packages
cd void-packages/
./xbps-install binary-bootstrap
```

After that, clone the void-templates somewhere

```bash 
git clone https://github.com/elbachir-one/void-templates
cd void-templates/
cp -r brave/ fetch/ librewolf/ ~/void-packages/srcpkgs/
./xbps-install pkg <pkgname>
```

That's it for now. More packages will be added in the future.
