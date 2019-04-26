# reposync

## Deploy

```
gcloud functions deploy reposync \
  --entry-point F \
  --set-env-vars "GITHUB_TOKEN=<github-token>" \
  --runtime go111 \
  --trigger-http
```
