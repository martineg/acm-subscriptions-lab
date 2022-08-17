ACM subscription lab resources

# Git channel subscriptions to Helm charts

Run `bootstrap.sh` to apply the `git-sub` resources to the hub cluster to add individual subscriptions for Helm charts hosted in the same repository.

The `helloworld` subscription demonstrates how to override Chart values using _packageOverrides_ in the subscription.

## Multiple charts

the `multiple-charts` branch demonstrates subscribing to multiple Helm charts hosted in a Git repository, using individual subscriptions per chart following the "subscription of subscriptions" model.

---

This repo was created using inspiration from https://github.com/mikeshng/git-sub-for-helm-sub as base for a "subscription of subscriptions" model tracking Charts from Git. The `helloworld` and `mortgage` helm charts are from https://github.com/stolostron/application-lifecycle-samples/.
