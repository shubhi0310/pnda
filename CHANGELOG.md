# Change Log
All notable changes to this project will be documented in this file.

## Unreleased
### Changed
- PNDA-3249: Upgrade Kafka version to 0.11.0.0

## [0.2.0] 2017-08-01
### Added
- PNDA-2452: Add high level overview of creating PNDA
- PNDA-2691: Add jupyterproxy upstream project
- PNDA-2693: Script to setup RPM and DEB package mirrors
- PNDA-2782: Support RHEL builds
- PNDA-2836: Scripts to update existing deb, rpm and python mirrors with new packages
- PNDA-2843: Specify explicit versions for all python modules
- PNDA-2874: Add snappy compression libraries for deb and rpm mirrors
- PNDA-2903: Obtain nodejs as tar.gz instead of deb/rpm
- PNDA-2944: Add RedHat license checks
- Add graphite-api packages for offline
- Synchronize the package index files after adding new sources
### Changed
- PNDA-2537: update mirror deb/rpm script in order to pinned top level version
- PNDA-2880: Pin 'sbt' to version 0.13.13
- PNDA-2894: review repo org and update documentation
- PNDA-2810: Update version of boto
- PNDA-2984: Upgrade JDK to 8u131
- Fix Cloudera dependencies at 5.9.0
### Fixed
- PNDA-2717: Replace wget with curl
- Fix Anaconda version at 4.0.0

### Added
- PNDA-2445: Support for Hortonworks HDP hadoop distro.

## [0.1.1] 2017-01-20
### Changed
- Updated dependencies for build tools

## [0.1.0] 2016-12-12
### First version
- Top level repository and build system for PNDA
