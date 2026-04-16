# Document Title

> [!TIP]
> This repository is the working area for The Gathering Stream draft, "Document Title".

## Quick links

- [Editor's Copy](https://TG-Community.github.io/draft-cranstoun-mx-extensions/)
- [Stream Draft Record](https://stream.tg.community/doc/draft-cranstoun-mx-extensions)
- [Latest Release](https://github.com/TG-Community/draft-cranstoun-mx-extensions/releases/latest)
- [Stream Draft Content Guidelines](https://tg.community/authors/stream-draft/content-guidelines)

## How to publish your draft on Stream

> [!IMPORTANT]
> Make sure your GitHub account is connected to your Stream account in [Profile Settings](https://stream.tg.community/profile).

1. Commit your draft updates to the `main` branch.
2. Open the repository on GitHub and go to **Releases**.
3. Click **Draft a new release**.
4. In **Tag**, create a release tag for this publication.
   Use `draft-cranstoun-mx-extensions-00` for the first published version.
   Use `draft-cranstoun-mx-extensions-01`, `draft-cranstoun-mx-extensions-02`, and so on for later versions.
5. Keep the release target set to `main`.
6. Set the release title. Using the same value as the tag is recommended.
7. Click **Publish release**.
8. Wait for the GitHub Actions release workflow to finish.
   That workflow publishes the editor's copy, creates the versioned artifacts, and syncs the draft to Stream.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for contribution guidance.

## Local build

Build the editor's copy and text output with:

```bash
npm install
npm run build
```
