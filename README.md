# LinguaPilot AI for macOS - Client Guide

Official website: https://linguapilot.netlify.app/

Support email: simdev24@gmail.com

Thank you for using LinguaPilot AI. This guide explains how to install, configure, activate, and use the macOS version.

## What LinguaPilot AI Does

LinguaPilot AI helps you correct, improve, rewrite, translate, and understand selected text from everyday applications such as Microsoft Word, email, browser forms, notes, messages, and professional writing tools.

Select text, press the configured shortcut, and LinguaPilot AI displays a suggestion popup with an improved version, explanations, and copy/replace actions.

## What Is Included

- `LinguaPilotAI-macOS.dmg`: the macOS installer package to give to clients.
- `Tutorials/LinguaPilot_macOS_Setup_Guide.pdf`: full step-by-step setup guide.
- `README.md`: this client guide.
- `PRODUCT_DESCRIPTION.md`: product overview and sales/support description.

## Installation On macOS

1. Open `LinguaPilotAI-macOS.dmg`.
2. Drag `LinguaPilot AI.app` into the `Applications` folder.
3. Open the app from `Applications`, not directly from the DMG.
4. If macOS blocks the app because it is from an unidentified developer, right-click the app, choose `Open`, then confirm.
5. Keep the app installed in `Applications` so automatic startup and macOS permissions work correctly.

## Required macOS Permissions

LinguaPilot AI needs permission to listen for a global shortcut and send `Command+C` to the active application so it can read the text you selected.

After installing the app:

1. Open `System Settings`.
2. Go to `Privacy & Security`.
3. Open `Accessibility`.
4. Add and enable `LinguaPilot AI.app`.
5. Go back to `Privacy & Security`.
6. Open `Input Monitoring`.
7. Add and enable `LinguaPilot AI.app`.
8. Quit and reopen LinguaPilot AI.

If the shortcut is detected but no selected text is captured, check these permissions again.

## Quick Start

1. Launch LinguaPilot AI from `Applications`.
2. Open `Settings / API`.
3. Choose your provider:
   - `Gemini`: Google AI mode, requires a Gemini API key.
   - `OpenAI`: high-quality cloud mode, requires an OpenAI API key.
   - `Ollama`: local/private mode, requires Ollama and a local model.
4. Paste your API key if using Gemini or OpenAI.
5. Click `Test provider`.
6. Select text in Word, Notes, email, or another app.
7. Press the default shortcut:

```text
Control + Option + Command + L
```

8. Review the suggestion popup.
9. Copy the improved text or replace the original selection.

## Recommended Providers

Gemini is a simple first choice for many users because setup is quick with Google AI Studio.

OpenAI is recommended when you want strong writing quality and consistent professional rewriting.

Ollama is recommended when privacy is the priority and you want local AI processing without cloud API usage.

## Automatic Startup

LinguaPilot AI can start automatically with macOS. In Settings, enable:

```text
Start automatically with macOS
```

The app is designed to launch after macOS finishes loading the user session so the global shortcut permission is available.

If the shortcut does not work after a reboot, quit LinguaPilot AI and open it again from `Applications`. Then verify the app is enabled in `Accessibility` and `Input Monitoring`.

## Trial And License

LinguaPilot AI includes a local trial and hardware-bound license activation.

To activate:

1. Open LinguaPilot AI.
2. Open `Settings / API`.
3. Open the `License` section.
4. Copy your `Machine ID`.
5. Send your purchase email and Machine ID to support.
6. Enter the activation key you receive.

## Support

Website: https://linguapilot.netlify.app/

Email: simdev24@gmail.com

For support, include:

- Your macOS version.
- Your selected provider: Gemini, OpenAI, or Ollama.
- A short description of the issue.

## Important Notes

- API tokens are used only when you request a correction.
- LinguaPilot AI does not consume Gemini/OpenAI tokens while it is only listening.
- Ollama mode runs locally and does not use cloud API tokens.
- For best results, install the app in `Applications` and grant the required macOS permissions.
