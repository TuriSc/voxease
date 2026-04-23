# VoxEase Communication Aid

A self-contained, offline-capable web application for augmentative and alternative communication (AAC). This experimental application can help individuals with speech, sight, or language impairments communicate using pre-defined phrases or custom messages with text-to-speech support.

Try it here: [turisc.github.io/voxease](https://turisc.github.io/voxease/)

## Features

### Core Communication

- **Pre-defined Phrases**: Quick access to common phrases organized in a grid or list layout
- **Custom Messages**: Type custom messages using on-screen or physical keyboard
- **Text-to-Speech**: Speak phrases and messages using Web Speech API with adjustable speech rate
- **Speak Toggle**: Quick toggle button to enable/disable automatic speech
- **Multi-language Support**: Full interface and content translations for:
  - English
  - Italian (Italiano)
  - Spanish (Español)
  - German (Deutsch)
  - French (Français)
  - Ukrainian (Українська)
  - Dutch (Nederlands)
  - Basque (Euskara)
  - Greek (Ελληνικά)
  - Norwegian (Norsk)

### Input Methods

- **Mouse/Touch**: Click or tap phrases and buttons. Hover mode available
- **Physical Keyboard**: Full typing support when composing messages
- **On-screen Keyboard**: Virtual keyboard with QWERTY and ABC layouts, including number row
- **Gamepad/Controller**: Full Xbox/PlayStation controller support with customizable navigation
- **Auto-scan Mode**: Automatic scanning through phrases with configurable timing

### Accessibility

- **Screen Reader Support**: Comprehensive ARIA labels and live regions
- **Dark Mode**: For visual accessibility
- **Large Touch Targets**: Optimized button sizes helping with motor impairments
- **Visual and Audio Feedback**: Confirmation sounds and visual cues for interactions
- **Symbol Support**: Icon/emoji display alongside text for visual learners

### Offline Capability

- **Self-contained**: Works without Internet connection
- **Single File**: All assets embedded, works from file:// protocol
- **No Dependencies**: No external libraries or resources required
- **Progressive Web App (PWA)**: Installable on mobile devices
- **Completely private**: No tracking or analytics, and no data sent to external servers

### Personalization

- **Settings Persistence**: All preferences saved to browser localStorage
- **Phrase Management**: Edit, reorder, and delete phrases via a dedicated Phrases modal
- **Export/Import**: Backup and restore settings and phrase registry
- **Input Method Preferences**: Enable/disable specific input methods
- **UI Customization**: Adjust colors, speech rate, and interaction modes

## Getting Started

### Install as PWA (recommended)

1. Open [turisc.github.io/voxease](https://turisc.github.io/voxease/)
2. Look for "Install" or "Add to Home Screen" option in your browser menu
3. Launch from your home screen or app menu

### Use from source

1. Download `index.html`
2. Open it in any modern web browser with Web Speech API support and Gamepad API support (Chrome, Firefox, Safari, Vivaldi, Edge)
3. Start using immediately - no installation required, works offline

## Usage

### Gamepad Controls

- **D-pad / Left Stick**: Navigate between phrases
- **LB / LT**: Navigate left/right (LT inverted to go right)
- **RB / RT**: Navigate left/right (RT inverted to go left)
- **A Button (Xbox) / X Button (PS)**: Activate selected phrase
- **B Button (Xbox) / Circle (PS)**: Cancel/close modals

### Managing Phrases

1. Click the "Phrases" button in the control bar
2. The Phrases modal shows all phrases in an editable list
3. Edit any phrase's text or icon
4. Reorder phrases with the up/down arrow buttons
5. Delete phrases with the trashbin button
6. Add new phrases using the text and icon inputs at the bottom

### Export/Import Settings

- **Export**: Click "Export Settings" to download a JSON file with all your preferences
- **Import**: Click "Import Settings" and select a previously exported JSON file

## Disclaimer

**THIS IS NOT A MEDICAL DEVICE.** This software is not approved, cleared, or certified by any medical regulatory authority. It is provided as-is for personal, educational, and experimental use only.
This application should NOT be relied upon in emergency or life-threatening situations.
Users should consult with qualified healthcare professionals and certified speech-language pathologists for proper AAC assessment and device recommendations. For medical-grade AAC solutions, please use devices and software specifically approved for medical use by appropriate regulatory authorities.

USE AT YOUR OWN RISK. The developer assumes no liability for any consequences of using this software.

## Version history

- 2026.04.22 - v1.0.5
  - Add language locales and voice names
  - Change light and dark color themes to Solarized
  - UI fixes
- 2026.03.08 - v1.0.4
  - Add Phrases modal for editing, reordering, and deleting all phrases
  - Add Norwegian language (thanks @FSjursaether)
- 2026.03.01 - v1.0.3
  - Add Ukrainian, Dutch, Basque languages (thanks @nykula, @JayVisschedijk, @xezpeleta), Greek
  - Select browser language and matching keyboard layout automatically
  - Speak output banner text on click
  - Scroll view in scanning mode
  - Sort phrases by urgency
  - Fix output banner and disclaimer display on small screens
- 2026.02.24 - v1.0.0 - First release

## More Information

VoxEase is an original project.

For more information, visit [turiscandurra.com](https://turiscandurra.com/)
