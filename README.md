# deploy-orb

[![CircleCI](https://circleci.com/gh/netgaintechnology/orb-deploy-orb.svg?style=svg)](https://circleci.com/gh/netgaintechnology/orb-deploy-orb) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

An  orb managing the deployment phase jobs.

## Usage

For full usage guidelines, see the [orb registry listing](http://circleci.com/orbs/registry/orb/netgaintechnology/orb-deploy-orb).

### Example

Following is an example of a deployment pipeline.

```yaml
version: 2.1

orbs:
  deploy-orb: netgaintechnology/deploy-orb@x.y.z

workflows:
  version: 2
  deployment:
    jobs:
      - deploy-orb/terraform_deploy
```

## Contributing

We welcome [issues](https://github.com/netgaintechnology/orb-deploy-orb/issues) to and [pull requests](https://github.com/netgaintechnology/orb-deploy-orb/pulls) against this repository!
