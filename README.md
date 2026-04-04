# UConnect Mock GitOps

GitOps repository for the dedicated mock control cluster.

It manages:

- the mock application stack in `apps/overlay/staging`
- Argo Rollouts on the dedicated mock cluster via `platform/rollout/install`
- ImageUpdater resources consumed by the central Argo CD Image Updater via `platform/updater/staging`
