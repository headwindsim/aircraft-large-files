![Headwind Simulations](https://headwindsim.net/assets/images/headwind-logo-light.png)

# Headwind Simulations Aircraft Large Files

### Requirements

- git client
- NodeJS with pnpm

### Initial Setup

Clone the repository either individually or as a submodule of the aircraft repository. Then run `pnpm install`.

### Modifying a large file

Run `pnpm unchunk` to combine the files that are stored in chunks of maximum 100MiB.

To commit a change, simply create a commit. The pre-commit hook will automatically run `pnpm chunk` to split large files.

## License

This repository is a derivative work based on [FlyByWire Simulations](https://github.com/flybywiresim) Aircraft Large Files, modified by Headwind Simulations.

Original source code assets present in this repository are licensed under the GNU GPLv3.
Original 3D assets are licensed under CC BY-NC 4.0.

Modifications made by Headwind Simulations are likewise released under the same respective licenses (GPLv3 / CC BY-NC 4.0).

Microsoft Flight Simulator © Microsoft Corporation. 

This add-on was created under Microsoft's "Game Content Usage Rules" using assets from Microsoft Flight Simulator, and it is not endorsed by or affiliated with Microsoft.

The contents of distribution packages built from the sources in this repository are therefore licensed as follows:

- in the case of original source code from FBW or Headwind, or compiled artifacts generated from it, under GPLv3.
- in the case of original 3D assets from FBW or Headwind, under CC BY-NC 4.0.
- in the case of assets covered by the "Game Content Usage Rules", under the license granted by those rules.