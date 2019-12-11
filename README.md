# oci-qualys

This is a Terraform module that deploys [Qualys](https://www.qualys.com/)  on [Oracle Cloud Infrastructure (OCI)](https://cloud.oracle.com/en_US/cloud-infrastructure).  It is developed jointly by Oracle and Qualys.

## Qualys Virtual Scanner

[Qualys Virtual Scanner Appliance](https://cloudmarketplace.oracle.com/marketplace/app/qualys-oci_scanner) is a stateless, disposable resource which acts as an extension of Qualys Cloud Platform and can run in the Oracle Cloud Infrastructure from the [Oracle Cloud Marketplace](https://cloudmarketplace.oracle.com/marketplace/oci). This scanner, once deployed, will function as a standard Virtual Scanner and can scan based on IP address or CIDR block. Detailed instructions for launching virtual scanner is available in the [virtual-scanner](./virtual-scanner/README.md) space.

## Terraform Version

Terraform v0.12+ is required.
