# Security policy

## Reporting a vulnerability

Report vulnerabilities privately through GitHub: open the affected
repository, go to **Security > Report a vulnerability**. Do not open a
public issue, discussion or pull request for a security problem.

Include what you found, how to reproduce it, and the impact you expect.
We acknowledge reports within 3 working days and keep you updated until
the issue is fixed and disclosed.

## Supported versions

Only the latest release of each repository receives security fixes.
Public runner AMIs older than the latest build are not patched; rebuild
or move to the newest image.

## Scope

In scope: the scaler, the boot agent, the runner images and the Terraform
module, including the IAM permissions and network exposure they create.

Out of scope: vulnerabilities in GitHub Actions itself, in AWS services,
or in third-party actions run by your workflows.
