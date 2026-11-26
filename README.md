# Safa — Android (Google Play)

Trusted Web Activity wrapper for the Safa website (package `com.theonenetwork.safa`).

## Build

GitHub Actions builds an unsigned `.aab` and `.apk` on every push to `main` and on pull requests.
Download them from the workflow run's **Artifacts** section.

Locally:

```bash
./gradlew bundleRelease assembleRelease
```

Outputs land in `app/build/outputs/`. Build outputs are not committed to the repo.

## Signing

Signing happens privately, outside GitHub. Never commit keystores or `keystore.properties`.

## Workflow

Work on `feature/short-description` branches and open a Pull Request into `main`.
