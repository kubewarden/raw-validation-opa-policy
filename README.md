> [!important]
> **notice:**
> starting from kubewarden release 1.32.0, all code from this repository has been merged into [github.com/kubewarden/policies](https://github.com/kubewarden/policies), which is now a monorepo containing policies.
> please refer to that repository for future updates and development.
> **this repository is now archived. development continues in the new location.**



[![Kubewarden Policy Repository](https://github.com/kubewarden/community/blob/main/badges/kubewarden-policies.svg)](https://github.com/kubewarden/community/blob/main/REPOSITORIES.md#policy-scope)
[![Stable](https://img.shields.io/badge/status-stable-brightgreen?style=for-the-badge)](https://github.com/kubewarden/community/blob/main/REPOSITORIES.md#stable)

# Kubewarden policy raw-validation-opa-policy

## Description

This is an OPA test policy that validates a raw request.

It accepts a raw request that contains a `user` field with the value: `"tonio"`.
It rejects all the other requests.

## Settings

This policy has no configurable settings.
