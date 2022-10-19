# Terraform binary verifications

## Terraform signature and PGP verification

Terraform binaries are verified against both there SHA256SUMS and signatures after donwload.

Theses files need to be added to the [/security](https://github.com/zenika-open-source/terraform-aws-cli/tree/master/security) folder.

They can be downloaded from the [official Terraform releases](https://releases.hashicorp.com/terraform).

## Hashicorp signature verification

Both Terraform SHA256SUM and signature files are verified against [Hashicorp public GPG key](https://www.hashicorp.com/security).
