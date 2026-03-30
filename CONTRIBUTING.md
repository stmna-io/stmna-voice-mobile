# Contributing to STMNA_Voice Mobile

Thanks for your interest in contributing. This guide covers the essentials for Android app contributions. For backend/pipeline contributions, head to the [stmna-voice](https://github.com/stmna-io/stmna-voice) repo.

## Getting Started

1. Fork the repository
2. Clone your fork and open the project in Android Studio
3. Build and run on a device or emulator (see the [Build Guide](docs/build-guide.md))
4. Create a feature branch from `main`

## What We're Looking For

- **Accessibility improvements:** Screen reader support, better contrast, keyboard navigation
- **IME behavior fixes:** Edge cases with specific apps, cursor positioning, text field types
- **Language and locale testing:** Verify the app works correctly across different Android versions, OEMs, and locales
- **Bug fixes:** Especially with device-specific audio recording issues
- **UI improvements:** Kotlin/Compose enhancements to the keyboard layout or settings page

## Code Style

- Follow existing Kotlin conventions in the project
- Keep the codebase simple and readable
- Add comments for non-obvious logic
- Test on a real device when possible (IME behavior varies between emulators and real hardware)

## Submitting Changes

1. Keep pull requests focused on a single change
2. Include a clear description of what changed and why
3. If fixing a bug, mention the device model and Android version where you reproduced it
4. Screenshots or screen recordings help reviewers understand UI changes

## Bug Reports

When filing a bug report, include:

- **Device model** (e.g. Pixel 8, Samsung Galaxy S24)
- **Android version** (e.g. Android 14)
- **App version** (check in the app settings)
- **STMNA_Voice backend version** (if relevant)
- **Steps to reproduce**
- **Expected vs. actual behavior**
- **Logcat output** if available (the app has a "Generate Recent Logcat" option)

## Out of Scope

These belong in the [stmna-voice](https://github.com/stmna-io/stmna-voice) repo:

- Backend/pipeline changes
- Whisper model configuration
- Server deployment or infrastructure
- Linux desktop client

## License

By contributing, you agree that your contributions will be licensed under GPLv3, consistent with the project license.
