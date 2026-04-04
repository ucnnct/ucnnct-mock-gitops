# UConnect Mock GitOps

GitOps repository for the dedicated mock control cluster.

It manages:

- the mock application stack in `apps/overlay/staging`
- Argo Rollouts in `platform/rollout/install`
- Argo CD Image Updater in `platform/updater/install`
- ImageUpdater resources for the staging mock stack in `platform/updater/staging`
