# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.2]

### Added

- Get-IpNetworkBase
- Documentation for new function

### Updated

- IpNetwork Class instantiator uses Get-IpNetworkBase to set the IpAddress of the resultant object
- about_Ip.Tools discusses use of Class
- Pester Tests now load module using **Using**

### Fixed

- Not using the Network Base address when defining an IpNetwork caused some Test-IpInNetwork tests to fail
- Linting issues from first run(s) of MegaLinter on this repo

## [0.0.1] - 2021-11-26

### Added

- Initial release of IP.Tools
- Convert-MaskLenToIp
- New-IpNetwork
- Get-IpBogon
- Test-IpInNetwork
- Test-IpBogon
- Remove-IpBogon

### Changed

- Nothing

### Deprecated

- Nothing

### Removed

- Nothing

### Fixed

- Nothing

### Security

- Nothing

### Known Issues

- [#1](https://github.com/jberkers42/ip.tools/issues/1) Linting Issue from first run of Mega-Linter

[Unreleased]: https://github.com/jberkers42/ip.tools
[0.0.2]: https://github.com/jberkers42/ip.tools/releases/tag/v0.0.2
[0.0.1]: https://github.com/jberkers42/ip.tools/releases/tag/v0.0.1
