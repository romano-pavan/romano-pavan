### Romano Pavan

Twelve years of keeping infrastructure running — Linux, networks, virtualization.
Now writing the same infrastructure as code, on AWS.

[![AWS Certified Solutions Architect – Associate](https://images.credly.com/size/110x110/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png)](https://www.credly.com/badges/86eaea56-6b6b-4b73-967f-5331b32c456c/public_url)

**Currently:** drilling Terraform toward the Associate exam.
**Next:** a zero-trust security project — AWS Organizations, GuardDuty, Security Hub.

---

#### Projects

| | |
|---|---|
| [**adria-stay**](https://github.com/romano-pavan/adria-stay) | A multi-tier AWS environment written entirely in Terraform. Custom VPC across two AZs, autoscaling behind an ALB, RDS with a managed master password, private S3 behind CloudFront with OAC, and a GitHub Actions pipeline authenticating over OIDC. No long-lived keys, no open SSH ports, every decision written down as an ADR. |
| [**tf-starter**](https://github.com/romano-pavan/tf-starter) | The five config files every Terraform project needs, already written. Clone it and start building. |

---

#### Stack

`Terraform` · `AWS` · `Linux` · `Bash` · `PowerShell` · `Git` · `GitHub Actions` · `Proxmox` 

---

What I optimise for: no static credentials, no secrets in state, no manual
changes outside the code, and a bill that drops to near zero when nothing
is running.