# Installation 

`
wget -q -O /usr/bin/samcf "https://raw.githubusercontent.com/syfqsamvpn/wgcf/main/wgcf.sh" && chmod +x /usr/bin/samcf && samcf
`

# wgcf-config-updater

`wgcf-config-updater` is a simple bash script that updates and generates a new WireGuard configuration using `wgcf`.

## Requirements

This script requires `wgcf` to be installed. If it's not installed, the script will automatically download and install it.

## Usage

./wgcf-config-updater.sh [OPTIONS]...

Options:

* `-h`, `--help`: Display the help message and exit.
* `--key KEY`: Specify the new license key KEY.

If you run the script without any options, it will prompt you to enter a new license key.

## Example

./wgcf-config-updater.sh --key abcdef1234567890

This will update the configuration with the new license key `abcdef1234567890`.
