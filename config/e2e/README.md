# E2E Test Configuration

This directory contains configuration for deploying `signer-ca` for end-to-end testing.

It includes `kustomize` configuration and patches for deploying `signer-ca` with a sample CA file.
The sample CA is automatically generated by `cfssl`
following the example in [Kubernetes: The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way/blob/master/docs/04-certificate-authority.md).
