# Scoop Bucket for Nostr

[![Tests](https://github.com/nostorg/scoop-nostr/actions/workflows/ci.yml/badge.svg)](https://github.com/nostorg/scoop-nostr/actions/workflows/ci.yml) [![Excavator](https://github.com/nostorg/scoop-nostr/actions/workflows/excavator.yml/badge.svg)](https://github.com/nostorg/scoop-nostr/actions/workflows/excavator.yml)

## How do I install these manifests?

First install [scoop](https://scoop.sh/). Then add the bucket:

```
scoop bucket add nostr https://github.com/nostorg/scoop-nostr
```

Finally install a `<manifest>` (such as `gossip` or `lume`):

```
scoop install <manifest>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
