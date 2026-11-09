# Nuri Launcher

Nuri Launcher is an independent, non-commercial Windows desktop launcher for Minecraft: Java Edition.

## Purpose

This project is a personal hobby project created to learn how a custom Java Edition launcher works. It is currently intended for use by the developer.

## Authentication and ownership

Nuri Launcher uses:

- Microsoft OAuth 2.0 Device Code Flow
- Xbox Live authentication
- XSTS authentication
- Minecraft Services APIs

The launcher requires successful Microsoft authentication and verifies that the signed-in account owns Minecraft: Java Edition before enabling gameplay. It does not bypass authentication, game ownership checks, or other safety features.

## Privacy

- Microsoft account passwords are never collected.
- Authentication tokens are stored locally on the user's Windows device.
- Authentication information is not transmitted to an external developer-operated server.
- No client secret is embedded in the application.

## Features

- Microsoft account authentication
- Java Edition ownership verification
- Installation and launching of official game versions
- Planned Fabric and NeoForge support
- Planned Iris shader support
- Planned local world backup and version upgrade tools

## Project status

Nuri Launcher is currently under development and is not ready for public distribution.

## Disclaimer

Nuri Launcher is an independent project and is not affiliated with, endorsed by, or sponsored by Microsoft or Mojang.
