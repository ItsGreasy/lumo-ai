# Lumo AI

Lumo is a self-hosted AI assistant project built around local language models and optional integrations.

This public repository currently contains **project information and OAuth disclosure pages only**. It is **not** a published copy of the private Lumo deployment or its source code. A reusable, open-source Command Center is planned for a later stage.

- [Project homepage](./index.md)
- [Privacy policy](./privacy.md)

## Google Calendar integration

An optional Google Calendar connection is under development. Its intended purpose is to read and create events on an explicitly approved family calendar after authorization. Calendar writes require confirmation.

**Current status:** Integration implementation has been tested offline. Public repository content does not indicate that any live Google account has been enrolled.

## Security and publication

Do not commit OAuth client JSON, access or refresh tokens, API keys, bot tokens, private calendar data, personal documents, logs, host configuration, or other secrets to this repository. A `.gitignore` is not a substitute for reviewing changes before publication.

For questions about the project or privacy policy, contact [greasebotai@gmail.com](mailto:greasebotai@gmail.com).

## License

Repository content is subject to the [LICENSE](./LICENSE) file. Any future source release will be reviewed separately before publication.
