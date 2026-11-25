---
title: InPlacePodVerticalScalingExclusiveCPUs
content_type: feature_gate
_build:
  list: never
  render: false

stages:
  - stage: alpha
    defaultValue: false
    fromVersion: "1.32"
---
Enables in-place CPU resizing for containers in pods with Guaranteed QoS class
that use exclusive CPUs allocated by the static CPU manager policy.
Requires the static CPU manager
policy on the node.
