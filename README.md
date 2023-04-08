# go-openvswitch    ![GitHub release (latest SemVer)](https://img.shields.io/github/v/tag/neaas/go-openvswitch?display_name=tag&label=%20&sort=semver)  ![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/neaas/go-openvswitch/go.yml?label=%20&logo=github)
[![Go Reference](https://pkg.go.dev/badge/github.com/neaas/go-openvswitch.svg)](https://pkg.go.dev/github.com/neaas/go-openvswitch)

Go packages which enable interacting with Open vSwitch and related tools. Apache 2.0 Licensed.

- `ovs`: Package ovs is a client library for Open vSwitch which enables programmatic control of the virtual switch.
- `ovsdb`: Package ovsdb implements an OVSDB client, as described in RFC 7047.
- `ovsnl`: Package ovsnl enables interaction with the Linux Open vSwitch generic netlink interface.

See each package's README for additional information.

--- 

## Changes

Other than some changes to push this as a go module under the `neaas` organization, CI updates, and style changes, this fork adds little to the [upstream](https://github.com/digitalocean) other than 1 key change. OvS bridge configurations can now be set beyond what has an explicit function. A PR has been made to the upstream focusing on this: digitalocean@[#117](https://github.com/digitalocean/go-openvswitch/pull/117).
