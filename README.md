# eb-deploy-s3

```
deploy:
  steps:
  - darthtrevino/eb-deploy-s3@<version>:
      access-key: $S3_KEY_ID
      secret-key: $S3_KEY_SECRET
      app-name: <enter app name>
      env-name: <enter env name>
      version-label: <enter version label>
      region: <enter region>
      s3-bucket: <enter s3 bucket name>
      s3-key: <enter file name>
```
