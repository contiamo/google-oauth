# Google OAuth


This repo contains our Helm chart for Google OAuth.


## App 

This chart installs the  `colemickens/oauth2_proxy` image.


## Installing:

```bash
helm repo add contiamo https://contiamo.github.io/google-oauth/
helm install contiamo/google-oauth
```

## Updating

The updates are managed by a Github Action workflow based on [Helm releaser](https://github.com/helm/chart-releaser-action)

*To Update* 
1. Make your changes
2. Bump the chart version
3. Merge/push to `main`
4. The workflow will release it for you. It usually takes about a minute and 30 seconds to create a new chart release after merging the code to `main`. 

