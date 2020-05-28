# terraform-fmt-precommit

## A pre-commit hook which checks against Terraform format

### Instructions
1. Clone this repository
1. Ensure pre-commit is executable: `chmod +x pre-commit`
1. Copy `pre-commit` into `<repository-to-check>/.git/hooks/pre-commit`

Now if you attempt a `git commit` from `<repository-to-check>` and the source is unformatted, the commit will be blocked.

Note: `git commit --no-verify` will bypass any checking, and force the commit.