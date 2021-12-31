# OpenChrom Snap Package

## Install

    sudo snap install openchrom

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Development

### Build
    snapcraft

### Test
    sudo snap remove --purge openchrom
    sudo snap install openchrom*.snap --dangerous
    sudo snap connect openchrom:openchrom-dot-dir
    /snap/bin/openchrom
