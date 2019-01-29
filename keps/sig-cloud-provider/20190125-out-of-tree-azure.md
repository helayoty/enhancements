---
title: Support Out-of-Tree Azure Cloud Provider
authors:
  - @andrewsykim
owning-sig: sig-cloud-provider
participating-sigs:
  - sig-azure
reviewers:
  - TBD
approvers:
  - TBD
editor: TBD
creation-date: 2019-01-25
last-updated: 2019-01-25
status: provisional

---

# Supporting Out-of-Tree Azure Cloud Provider

## Table of Contents

* [Table of Contents](#table-of-contents)
* [Release Signoff Checklist](#release-signoff-checklist)
* [Summary](#summary)
* [Motivation](#motivation)
   * [Goals](#goals)
   * [Non-Goals](#non-goals)
* [Proposal](#proposal)
   * [Implementation Details/Notes/Constraints [optional]](#implementation-detailsnotesconstraints-optional)
   * [Risks and Mitigations](#risks-and-mitigations)
* [Design Details](#design-details)
   * [Test Plan](#test-plan)
   * [Graduation Criteria](#graduation-criteria)
   * [Upgrade / Downgrade Strategy](#upgrade--downgrade-strategy)
   * [Version Skew Strategy](#version-skew-strategy)
* [Implementation History](#implementation-history)

## Release Signoff Checklist

- [X] k/enhancements issue in release milestone and linked to KEP (https://github.com/kubernetes/enhancements/issues/667)
- [ ] KEP approvers have set the KEP status to `implementable`
- [ ] Design details are appropriately documentedbs
- [ ] Test plan is in place, giving consideration to SIG Architecture and SIG Testing input
- [ ] Graduation criteria is in place
- [ ] "Implementation History" section is up-to-date for milestone
- [ ] Supporting documentation e.g., additional design documents, links to mailing list discussions/SIG meetings, relevant PRs/issues, release notes

## Summary

Build support for the out-of-tree Azure cloud provider. This involves a well-tested version of the cloud-controller-manager 
that has feature parity to the kube-controller-manager. 

## Motivation

Motivation for supporting out-of-tree providers can be found in [KEP-0002](https://github.com/kubernetes/enhancements/blob/master/keps/sig-cloud-provider/0002-cloud-controller-manager.md). 
This KEP is specifically tracking progress for the Azure cloud provider.

### Goals

* Develop/test/release the Azure cloud-controller-manager
* Kubernetes clusters running on Azure should be running the cloud-controller-manager.

### Non-Goals

* Removing in-tree Azure cloud provider code, this effort falls under the [KEP for removing in-tree providers](https://github.com/kubernetes/enhancements/blob/master/keps/sig-cloud-provider/2019-01-25-removing-in-tree-providers.md).

## Proposal

### Implementation Details/Notes/Constraints [optional]

TODO for SIG-Azure

### Risks and Mitigations

TODO for SIG-Azure

## Design Details

### Test Plan

TODO for SIG-Azure

### Graduation Criteria

TODO for SIG-Azure

### Upgrade / Downgrade Strategy

TODO for SIG-Azure

### Version Skew Strategy

TODO for SIG-Azure

## Implementation History

TODO for SIG-Azure
