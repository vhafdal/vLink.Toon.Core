# vLink.Toon.Core Internal Development Docs

This space is for maintaining the `vLink.Toon.Core` contracts package.

The repo is intentionally small. Most changes affect one of three things:

- `ToonPropertyNameAttribute`
- shared enums in `ToonEnums.cs`
- package/build metadata in `vLink.Toon.Core.csproj`

## What this space should help with

- understanding the exact role of this package in the TOON stack
- keeping contract changes compatible across downstream repos
- knowing where package metadata and framework targets live
- making safe enum or attribute changes without surprising `vLink.Toon.Format` and `vLink.Toon.API.Formatters`

## Important repo reality

There is currently no checked-in test project in this repo. Validation is mainly:

- build and pack verification
- downstream validation in `vLink.Toon.Format` and `vLink.Toon.API.Formatters`

## Recommended reading order

1. `Architecture Overview`
2. `Public Surface and Compatibility`
3. `Build and Packaging`
4. `Change Cookbook`
