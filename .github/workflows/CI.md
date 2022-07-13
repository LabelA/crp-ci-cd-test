# GitHub Continuous Integration

This readme will guide you through the manual steps to complete the Continuous Integration setup.

## Enabling CI/CD

CI/CD is automatically enabled on GitHub when a repository has a `.github/workflows` folder in its root.

## Environment variables

1. Go to your project on GitHub
2. On your project's GitHub page, navigate to **Settings -> Secrets -> Actions -> New repository secret**

### Required variables

- `NPM_TOKEN`

### NPM_TOKEN

This variable is required to install @labela dependencies, which are protected. You can find the NPM token in 1Password. Search for `NPM Deploy` and copy the `NPM Token` value.
