# unitrust-demo
## Credential handling

Keep Gemini and other backend API keys in ignored local environment files or a deployment secret store. Commit only empty or clearly placeholder examples. Do not put backend keys in client bundles, comments, logs, issues, or archives. Keep service-account private keys outside the repository. `.gitignore` does not remove tracked files or old commits. Revoke any exposed key and check usage and billing. Firebase web API keys are client identifiers; restrict them to required Firebase APIs and exclude the Generative Language API. Use a separate backend Gemini key. See [Google credential response](https://docs.cloud.google.com/docs/security/compromised-credentials) and [Firebase API key guidance](https://firebase.google.com/docs/projects/api-keys).
