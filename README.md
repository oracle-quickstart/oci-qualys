# oci-qualys

This is a Terraform module that deploys [Qualys](https://www.qualys.com/)  on [Oracle Cloud Infrastructure (OCI)](https://cloud.oracle.com/en_US/cloud-infrastructure).  It is developed jointly by Oracle and Qualys.

## Qualys Virtual Scanner

[Qualys Virtual Scanner Appliance](https://cloudmarketplace.oracle.com/marketplace/app/qualys-oci_scanner) is a stateless, disposable resource which acts as an extension of Qualys Cloud Platform and can run in the Oracle Cloud Infrastructure from the [Oracle Cloud Marketplace](https://cloudmarketplace.oracle.com/marketplace/oci). This scanner, once deployed, will function as a standard Virtual Scanner and can scan based on IP address or CIDR block. Detailed instructions for launching virtual scanner is available in the [virtual-scanner](./virtual-scanner/README.md) space.

## Terraform Version

Terraform v0.12+ is required.

## Contributing

This project welcomes contributions from the community. Before submitting a pull request, please [review our contribution guide](./CONTRIBUTING.md)

## Security

Please consult the [security guide](./SECURITY.md) for our responsible security vulnerability disclosure process

## License

Copyright (c) 2019 Oracle and/or its affiliates.

Released under the Apache License Version 2.0 as shown at http://www.apache.org/licenses/.
