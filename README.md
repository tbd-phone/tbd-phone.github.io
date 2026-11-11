# tbd-phone.github.io

This repo serves TBD's phone loader at https://tbd-phone.github.io/.

Nothing here is edited by hand. `.github/workflows/deploy.yml` publishes the
`phone/loader/` folder of a commit on `main` in
[cheapsteak/tbd](https://github.com/cheapsteak/tbd), when that repo's
`phone-loader-deploy.yml` asks it to. The setup and the checks the deploy makes
are in [docs/phone-control-loader-repo.md](https://github.com/cheapsteak/tbd/blob/main/docs/phone-control-loader-repo.md).
