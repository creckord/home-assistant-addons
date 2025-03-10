# Changelog

## 4.12.8

- Add INWX DNS challenge support

## 4.12.7

- Add Hetzner DNS challenge support

## 4.12.6

- Add Azure DNS challenge support

## 4.12.5

- Fix another syntax error in runs script for rfc2136

## 4.12.4

- Fix syntax error in runs script for rfc2136
- Fix finish script for S6 V3

## 4.12.3

- Fix the DNS propagation delay setting for the rfc2136 provider

## 4.12.2

- Use HA wheels when possible during build

## 4.12.1

- Set preferred chain to "ISRG Root X1"

## 4.12.0

- Add support for custom Certbot auth and cleanup hooks
- Update Certbot 1.21.0 & Plugins
- Update to Python 3.9
- Update to Alpine 3.14
- Upgrade pip to 21.3.1
- Add missing ARG for BUILD_ARCH

## 4.11.0

- Add support for Njalla DNS

## 4.10.0

- Add support for custom ACME server and Certificate Authority

## 4.9.0

- Add support for DirectAdmin DNS

## 4.8.0

- Add support for Gandi DNS

## 4.7.1

- Adjust init settings

## 4.7.0

- Fix issue with DNS challenge
- Convert to s6-overlay

## 4.6.0

- Streamline propagation seconds
- Add propagation seconds to CloudFlare / option selection

## 4.5.0

- Update cerbot to 1.2.0
- Update image to Alpine 3.11
- Support CloudFlare API Token

## 4.4.0

- Added support for nectup dns

## 4.3.0

- Added support for google dns
- Fixed AWS support
- Updated documentation
- Update cerbot to 1.0.0

## 4.2.0

- Bugfix default empty dns setting

## 4.1.0

- Pin image to Alpine3.10
- Bugfix default options with empty dns

## 4.0.0

- Added support for dns challenges
