# List of guides

1. [Config](#config)
2. [How to run](#how-to-run)
3. [Docker](#docker)
4. [Enabling HTTPS](#enabling-https)
5. [Build from source](#build-from-source)
6. [Plugin usage](#plugin-usage)
7. [Plugin development](#plugin-development)
8. [Bulk import](#bulk-import)

## Config

See https://github.com/boi123212321/porn-vault/blob/dev/doc/config.md

## How to run

- Visit the [Releases](https://github.com/boi123212321/porn-vault/releases) page and download the latest version, for the platform of your choice
- Unzip the file
- Run the application in the terminal of your choice and follow the on-screen instructions
- Once your app is setup you can visit it on `http://localhost:3000` (or your LAN IP equivalent) in your web browser of choice

### Docker

See the [docker readme](doc/docker.md)

## Enabling HTTPS

- If you're on Windows you first need to download openssl, you can find the executables [here](https://wiki.openssl.org/index.php/Binaries)
- Generate a keypair using the command `openssl req -nodes -new -x509 -keyout server.key -out server.cert`
- Set the `ENABLE_HTTPS` flag in your config to true
- Change the `HTTPS_KEY` & `HTTPS_CERT` options to your generated key & cert file paths
- Open `https://localhost:3000`, ignore the self-generated certificate warning and enjoy an encrypted experience

## Build from source

See https://github.com/boi123212321/porn-vault/blob/dev/doc/build_from_source.md

## Plugin Usage

See https://github.com/boi123212321/porn-vault/blob/dev/doc/plugins_intro.md

## Plugin development

See https://github.com/boi123212321/porn-vault/blob/dev/doc/plugin_development.md

## Bulk import

See the [bulk import doc](import.md)
