# Scratch repo with CI for Fingolfin's smoke tests

Built by `scripts/scratch-ci-repo.sh` of the Fingolfin repo, whose `docs/agents/scratch-repo.md` says what is here.

Its one workflow, `.github/workflows/ci.yml`, runs on every push. It is red for as long as `ci.txt`, at the root of the repo, holds the line `red`.
