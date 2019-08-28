## Change Log

## v0.7.3
- Add support for `BlockDeviceMappings` and `IamInstanceProfile` parameters for
  `create_instance` workflow.

## v0.7.2
- Version bump to fix tagging issue. No code changes.

## v0.7.1
- Fix default tags parameter in `create_instance` workflow.

## v0.7.0
- Add `create_instance` workflow.

## v0.6.0
- Disable both the example workflows.
- Mark `token_code` on `assume_role` as a secret.
- Fix example `create_vpn_assume_role` workflow to correctly publish `credentials`
  and `assumed_role_user` details.
- Add `properties` to `credentials` on `boto3action` and `waiter`.

## v0.5.0
- Add missing CHANGES file.
- Update requirement on `boto3` so it's not so restrictive.
- Add `waiter` action.
- Add missing `config.schema.yaml`.
- Set credentials as `secret` on `boto3action`.

## v0.4.0
- Mark `credentials` as secret on `boto3action`.
- Add a simple config schema with a default region, which is not used.

## v0.3.0
- Move the examples from the `README` to be usable workflows:
  - create_vpc.
  - create_vpc_assume_role.
- Updates to `assume_role` so that it has an MFA option.

## v0.2.0
- First release of this pack.
- Migrate `aws` packs boto3 branch to a new pack instead of being on a branch.
