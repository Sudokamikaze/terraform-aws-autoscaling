# Changelog

All notable changes to this project will be documented in this file.

# [4.9.0](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.8.1...v4.9.0) (2021-11-22)


### Features

* add missing attributes to launch template, remove null resource for tag propagation, propagate default tags to instances, allow propagated name to be set independently of ASG ([#169](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/169)) ([f14ca13](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/commit/f14ca13e28c1af150d65a7cd6f9d35d0863e33ae))

## [4.8.1](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.8.0...v4.8.1) (2021-11-15)


### Bug Fixes

* update CI/CD process to enable auto-release workflow ([#168](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/168)) ([d0338a8](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/commit/d0338a8163c239a404d72bf9c57377b0eca62f68))

<a name="v4.8.0"></a>
## [v4.8.0] - 2021-11-15

- feat: add checkpoint_delay, checkpoint_percent to instance refresh ([#166](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/166))
- docs: Fixed max_instance_lifetime min value in description ([#165](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/165))


<a name="v4.7.0"></a>
## [v4.7.0] - 2021-10-08

- feat: Add support of time_zone inside schedules ([#164](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/164))


<a name="v4.6.0"></a>
## [v4.6.0] - 2021-09-02

- feat: Add support for `warm_pool` ([#142](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/142))
- docs: Updated description of user_data and user_data_base64 ([#161](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/161))


<a name="v4.5.0"></a>
## [v4.5.0] - 2021-08-25

- feat: Added throughput parameter for root and ebs block devices ([#160](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/160))


<a name="v4.4.0"></a>
## [v4.4.0] - 2021-06-12

- feat: Control propagation of the ASG Name tag to instances ([#152](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/152))


<a name="v4.3.0"></a>
## [v4.3.0] - 2021-06-11

- fix: Fix instance refresh ([#151](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/151))


<a name="v4.2.0"></a>
## [v4.2.0] - 2021-06-02

- feat: Adding autoscaling schedule ([#150](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/150))
- chore: update CI/CD to use stable `terraform-docs` release artifact and discoverable Apache2.0 license ([#146](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/146))
- chore: Updated versions&comments in examples ([#145](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/145))


<a name="v4.1.0"></a>
## [v4.1.0] - 2021-04-08

- fix: add tags to launch template ([#141](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/141))


<a name="v4.0.0"></a>
## [v4.0.0] - 2021-04-08

- feat: update module to include launch template support, mixed instances policy, instance refresh, etc. ([#139](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/139))
- chore: update documentation and pin `terraform_docs` version to avoid future changes ([#138](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/138))
- chore: align ci-cd static checks to use individual minimum Terraform versions ([#134](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/134))
- chore: only run validate check on min terraform version ([#133](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/133))
- chore: add ci-cd workflow for pre-commit checks ([#131](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/131))


<a name="v3.9.0"></a>
## [v3.9.0] - 2021-02-20

- chore: update documentation based on latest `terraform-docs` which includes module and resource sections ([#129](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/129))


<a name="v3.8.0"></a>
## [v3.8.0] - 2020-11-24

- fix: Updated supported Terraform versions ([#123](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/123))


<a name="v3.7.0"></a>
## [v3.7.0] - 2020-10-06

- fix: conver to dynamic tags to allow for empty values ([#119](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/119))


<a name="v3.6.0"></a>
## [v3.6.0] - 2020-08-13

- feat: aws-provider version bump to >= 2.41, < 4.0 ([#115](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/115))
- feat: base64 encoded user_data ([#107](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/107))
- fix: Changed owner to amazon in examples ([#105](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/105))


<a name="v3.5.0"></a>
## [v3.5.0] - 2020-04-10

- feat: Added max_instance_lifetime option for Auto Scaling Group ([#98](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/98))
- Updated aws_ec2 example with service_linked_role_arn
- Adds service_linked_role ([#77](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/77))
- Updated pre-commit hooks
- added encrypted option to root_block_device ([#78](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/78))
- Updated pre-commit hooks
- Fixed example (health_check to map of strings) ([#73](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/73))
- Update for Terraform 0.12 ([#68](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/68))


<a name="v2.12.0"></a>
## [v2.12.0] - 2019-11-08

- Added support for service_linked_role_arn (based on [#70](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/70))
- Corrected create launch configuration flag


<a name="v3.4.0"></a>
## [v3.4.0] - 2019-11-08

- Updated aws_ec2 example with service_linked_role_arn


<a name="v3.3.0"></a>
## [v3.3.0] - 2019-11-08

- Adds service_linked_role ([#77](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/77))


<a name="v3.2.0"></a>
## [v3.2.0] - 2019-11-08

- Updated pre-commit hooks
- added encrypted option to root_block_device ([#78](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/78))


<a name="v3.1.0"></a>
## [v3.1.0] - 2019-08-21

- Updated pre-commit hooks
- Fixed example (health_check to map of strings) ([#73](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/73))
- Update for Terraform 0.12 ([#68](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/68))


<a name="v2.11.0"></a>
## [v2.11.0] - 2019-06-08

- Corrected create launch configuration flag


<a name="v3.0.0"></a>
## [v3.0.0] - 2019-06-08

- Update for Terraform 0.12 ([#68](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/68))


<a name="v2.10.0"></a>
## [v2.10.0] - 2019-06-08



<a name="v2.9.1"></a>
## [v2.9.1] - 2019-01-01

- Fixed typo (closes [#49](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/49))


<a name="v2.9.0"></a>
## [v2.9.0] - 2018-11-23

- Added conditional for initial_lifecycle_hook parameter ([#52](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/52))
- Minor cleanup after [#45](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/45)


<a name="v2.8.0"></a>
## [v2.8.0] - 2018-08-18

- Fix to support externally created launch configurations (fix [#43](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/43)) ([#45](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/45))


<a name="v2.7.0"></a>
## [v2.7.0] - 2018-06-20

- Allow recreation of ASG when LC changes (fixes [#34](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/34)) ([#36](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/36))


<a name="v2.6.0"></a>
## [v2.6.0] - 2018-06-03

- Add lifecycle hooks create_before_destroy to the autoscaling group ([#33](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/33))


<a name="v2.5.1"></a>
## [v2.5.1] - 2018-05-16

- Updated headers in README.md


<a name="v2.5.0"></a>
## [v2.5.0] - 2018-05-16

- Added pre-commit hook to autogenerate terraform-docs ([#32](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/32))


<a name="v2.4.0"></a>
## [v2.4.0] - 2018-05-16

- Allow unlimited tags in ASG ([#31](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/31))


<a name="v2.3.0"></a>
## [v2.3.0] - 2018-04-23

- Enable spot_price on launch configuration ([#26](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/26))


<a name="v2.2.2"></a>
## [v2.2.2] - 2018-04-09

- Set default user_data to single char ([#24](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/24))


<a name="v2.2.1"></a>
## [v2.2.1] - 2018-03-15

- Fixed tags as maps bug ([#22](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/22))


<a name="v2.2.0"></a>
## [v2.2.0] - 2018-03-14

- Added readme about tags, updated example
- ref [#12](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/12) [#1](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/1) - resolve tagging format difference ([#19](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/19))


<a name="v2.1.0"></a>
## [v2.1.0] - 2018-01-11

- Launch configuration naming, tagging fix/clarity ([#11](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/11))
- Describe tag format ([#12](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/12))


<a name="v2.0.0"></a>
## [v2.0.0] - 2017-11-28

- Merge ASG and LC submodules into one, added conditional creation ([#10](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/10))


<a name="v1.2.0"></a>
## [v1.2.0] - 2017-11-26

- comment out output for target group arns ([#9](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/9))


<a name="v1.1.0"></a>
## [v1.1.0] - 2017-11-24

- Removed output of target_group_arns (closes [#7](https://github.com/terraform-aws-modules/terraform-aws-autoscaling/issues/7))


<a name="v1.0.4"></a>
## [v1.0.4] - 2017-11-22

- Disable output of load_balancers, because they are not always present


<a name="v1.0.3"></a>
## [v1.0.3] - 2017-10-04

- target_group_arns should be a list (workaround for issue: https://github.com/hashicorp/terraform/issues/13869)
- target_group_arns should be a list (workaround for issue: https://github.com/hashicorp/terraform/issues/13869)


<a name="v1.0.2"></a>
## [v1.0.2] - 2017-09-26

- Added ASG with ELB example


<a name="v1.0.1"></a>
## [v1.0.1] - 2017-09-26

- TF: Correct list all the way down
- TF: Fix passing list from main to ASG submodule


<a name="v1.0.0"></a>
## v1.0.0 - 2017-09-14

- Added all code and README
- Initial commit


[Unreleased]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.8.0...HEAD
[v4.8.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.7.0...v4.8.0
[v4.7.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.6.0...v4.7.0
[v4.6.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.5.0...v4.6.0
[v4.5.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.4.0...v4.5.0
[v4.4.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.3.0...v4.4.0
[v4.3.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.2.0...v4.3.0
[v4.2.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.1.0...v4.2.0
[v4.1.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v4.0.0...v4.1.0
[v4.0.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.9.0...v4.0.0
[v3.9.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.8.0...v3.9.0
[v3.8.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.7.0...v3.8.0
[v3.7.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.6.0...v3.7.0
[v3.6.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.5.0...v3.6.0
[v3.5.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.12.0...v3.5.0
[v2.12.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.4.0...v2.12.0
[v3.4.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.3.0...v3.4.0
[v3.3.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.2.0...v3.3.0
[v3.2.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.1.0...v3.2.0
[v3.1.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.11.0...v3.1.0
[v2.11.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v3.0.0...v2.11.0
[v3.0.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.10.0...v3.0.0
[v2.10.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.9.1...v2.10.0
[v2.9.1]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.9.0...v2.9.1
[v2.9.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.8.0...v2.9.0
[v2.8.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.7.0...v2.8.0
[v2.7.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.6.0...v2.7.0
[v2.6.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.5.1...v2.6.0
[v2.5.1]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.5.0...v2.5.1
[v2.5.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.4.0...v2.5.0
[v2.4.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.3.0...v2.4.0
[v2.3.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.2.2...v2.3.0
[v2.2.2]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.2.1...v2.2.2
[v2.2.1]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.2.0...v2.2.1
[v2.2.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.1.0...v2.2.0
[v2.1.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v2.0.0...v2.1.0
[v2.0.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.2.0...v2.0.0
[v1.2.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.0.4...v1.1.0
[v1.0.4]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.0.3...v1.0.4
[v1.0.3]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.0.2...v1.0.3
[v1.0.2]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.0.1...v1.0.2
[v1.0.1]: https://github.com/terraform-aws-modules/terraform-aws-autoscaling/compare/v1.0.0...v1.0.1
