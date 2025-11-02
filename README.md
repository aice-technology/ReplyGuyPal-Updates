# ReplyGuyPal Updates

This repository hosts the auto-update feed for [ReplyGuyPal](https://github.com/aice-technology/ReplyGuyPal_Mac), a macOS application that helps craft authentic replies on X (Twitter).

## About

This is a public repository that contains only the Sparkle appcast XML files used for automatic updates. The main application source code is maintained in a private repository.

## Files

- `appcast.xml` - Stable release update feed
- `appcast-beta.xml` - Beta release update feed (future)

## Update Mechanism

The ReplyGuyPal app checks this feed periodically to detect new versions. Updates are delivered via the [Sparkle framework](https://sparkle-project.org/).

### Appcast URL

```
https://raw.githubusercontent.com/aice-technology/ReplyGuyPal-Updates/main/appcast.xml
```

## Security

All updates are cryptographically signed using EdDSA signatures to ensure authenticity and integrity.

## Version History

See [appcast.xml](appcast.xml) for the complete version history.

---

**Note:** This repository is automatically updated by GitHub Actions when new releases are published.
