# Contributing

Thanks for contributing to this repository.

## Before you open a change

- Review the setup guidance in [`README.md`](./README.md).
- Keep changes focused on the AWS GitHub OIDC example and related documentation or workflows.
- Update documentation when behavior, setup steps, or required AWS resources change.

## Submitting changes

1. Create a branch for your work.
2. Make the smallest change that solves the problem.
3. Verify any updated workflow or policy files for correctness before submitting.
4. Open a pull request with a clear summary of what changed and why.

## Workflow-specific notes

- Keep AWS regions, IAM role names, resource names, and example paths consistent across docs, workflow files, and policies.
- Do not commit secrets, access keys, account credentials, or copied runtime outputs containing sensitive values.
- Mask sensitive values in workflow logs before exporting them to later steps.
