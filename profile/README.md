# hatchrun

Self-hosted GitHub Actions runners on your own AWS account. Fully open
source under Apache-2.0, nothing to buy, nothing phoning home.

Each job gets a fresh EC2 instance that boots in seconds, runs one job and
is gone. The images stay compatible with GitHub hosted runners where it
matters (the `runner` user, the tool cache, rootful Docker), so workflows
move over without changes.

| Repository | What it is |
| --- | --- |
| [hatchrun](https://github.com/hatchrun/hatchrun) | Scaler and boot agent (Go) |
| [images](https://github.com/hatchrun/images) | Runner AMIs: build pipeline and compatibility tests |
| [terraform-aws-hatchrun](https://github.com/hatchrun/terraform-aws-hatchrun) | Terraform module to deploy the whole stack |

Status: early development. Nothing here is ready for production yet.
