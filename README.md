# Void Templates

These are some additional Void Linux templates that are not included in
the official void-packages repository.

To use these templates:

```bash
git clone https://github.com/void-linux/void-packages
cd void-packages/
./xbps-src binary-bootstrap
```

After that, clone the void-templates somewhere

```bash
git clone https://github.com/elbachir-one/void-templates
cd void-templates/
cp -r <pkgname> ~/void-packages/srcpkgs/
./xbps-src pkg <pkgname>
```

That's it for now. More packages will be added in the future.
