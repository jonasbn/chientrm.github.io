---
title:  "Auto build GCP custom image with Cloud Build and Packer"
---

# Abstract

Google Cloud offer developers thousands of free and public machine images. They include famous Linux distributions like CentOS, Ubuntu, Debian, ... being built for both regular usages and specialized usages.

In many cases, developers want to create their own images, either for daily usage or business requirements.

There are many guides on setting up Cloud Build for image building. However, none of them point out common mistakes that can cause hours of logs tracing and retrying till you can get it works.

Thus, in this article, we will guide you on how to use Google Cloud Build to automate creating custom machine images and how to avoid those mistakes.

# Introduction

## Google Cloud Platform

GCP is one of the largest cloud platforms in the world, it has wide cloud computing, storage and networking.

If you are a new user, Google Cloud give you `$300` credit for 1 year free trial.

Furthermore, Cloud Build service offer free `120 minutes/day` of machine type `n1-standard-1`.

## Packer by HashiCorp

Packer is a free tool which use your cloud compute engine to create custom machine image. It has wide supports for Google Cloud Platform, Amazon Web Service, Azure and many more.

# Methods



# References

- [Building VM images using Packer](https://cloud.google.com/build/docs/building/build-vm-images-with-packer)
- [Google Compute Builder](https://www.packer.io/plugins/builders/googlecompute)