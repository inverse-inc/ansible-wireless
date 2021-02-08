# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v0.2.1]
### Added
- Remove kernel lines from hostapd install
- Add vlan file for dynamic vlan

## [v0.2.0]
### Added
- Remove mac80211hwsim module installation from hostapd
- Role `mac80211hwsim`

## [v0.1.2]
### Added
- Roles fix issues #1, #2, #3
  - Remove debug statements
  - No package matching 'linux-image-extra-4.19.0-9-amd64' is available
  - net pending/net commit are useless

## [v0.1.1]
### Added
- Role `hostapd` fix config installation

## [v0.1.0]
### Added
- Role `wpasupplicant` Allow to manage state of wpa_supplicant service
- Role `hostapd` host access point daemon
