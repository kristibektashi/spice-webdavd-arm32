# SPICE webdavd for ARM32

The source is taken from the ARM64 port of SPICE webdavd by the UTM project, and support for building for ARM32 has been added.

# Usage

1. Install [vspkg][1] with VS integrations
2. `.\vcpkg\vcpkg install glib:arm-windows`
3. Install [WiX v3.14.1 with ARM32 support][2] and [WiX Extension][3]
4. Open `spice-webdavd.sln` and build

[1]: https://github.com/microsoft/vcpkg
[2]: https://files.open-rt.party/Software/wix3-wix3141rtm-arm32-ship.zip
[3]: https://marketplace.visualstudio.com/items?itemName=WixToolset.WixToolsetVisualStudio2019Extension
