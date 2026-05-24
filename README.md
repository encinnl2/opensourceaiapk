# eAI Kawe

A cross-platform AI chat app that connects to multiple AI providers (OpenAI, Anthropic Claude, Google Gemini, Groq, DeepSeek, GitHub Copilot, local models, and many more).

## Getting Started

### Setting Up an AI Provider

Before you can chat, you need to configure an AI provider:

1. Tap the menu icon (top-left) to open the drawer
2. Go to Settings > API Config
3. Tap the + button to see available provider presets
4. Select a provider (e.g., OpenAI, Anthropic, Groq, or a free one like OpenGateway)
5. If the provider requires an API key, paste it in the API Key field
6. Tap "Fetch" to load available models, or type the model name manually
7. Tap Save
8. Tap the provider chip to select it as your active provider

For free providers like OpenGateway, no API key is needed - just select it and it works.

### GitHub Copilot Setup

1. Go to Settings > API Config
2. Find GitHub Copilot in the provider list or add it from presets
3. Tap "Login with GitHub"
4. A code and URL will appear - open the URL in your browser
5. Enter the code and authorize GitHub Copilot
6. Go back to the app and tap "I've authorized"

## Chatting

### Sending Messages

Type a message in the input bar at the bottom and tap the send button (arrow-up icon). The AI will respond in real-time with streaming text.

### Attaching Files

Tap the + button next to the input to open the attachment menu:

- **Photos & Images**: Select from gallery or take a photo with the camera. Images are automatically resized for efficient upload.
- **Documents**: Pick files like PDF, DOCX, TXT, spreadsheets, code files, and many more. The app supports 100+ file formats.
- Multiple files can be attached at once.

### Voice Input

Tap the microphone icon to record your voice. Tap it again to stop recording. The audio is transcribed using Whisper API and inserted into the input field.

### Stopping a Response

If the AI is generating a response and you want to stop it, tap the stop button (stop-circle icon).

### Undo Last Send

After sending a message, a small banner appears at the bottom for 3 seconds. Tap "Undo" to delete both your message and the AI's response.

## Features

### Plugins (Auto-Trigger)

The app includes built-in plugins that automatically activate based on what you type:

- **Web Search**: Type something like "search for latest AI news" or "cari informasi tentang react native"
- **URL Reader**: Paste any URL in your message and the app reads the page content
- **Calculator**: Type math expressions like "sqrt(144) + 25 * 3" or "hitung 15% dari 200000"
- **Translator**: Type "translate this to Indonesian: Hello, how are you?" or "terjemahkan ke Inggris: Saya suka kopi"
- **Summarizer**: Type "summarize this text: ..." or "ringkas artikel berikut"
- **Code Runner**: Send code with "run this code" or "analyze this function"
- **Image Generator**: Type "generate image of a sunset over mountains" or "buat gambar kucing lucu"

You can enable or disable plugins in the Plugins screen from the drawer menu.

### Smart Suggestions

After the AI responds, you'll see suggested follow-up questions or actions as small chips above the input bar. Tap one to send it immediately.

### File Generation

The AI can generate downloadable files. When it does, a download card appears in the chat. Tap "Save" to save the file to your device, or "Download" to share it via other apps. Supported formats include:

- Excel spreadsheets (.xlsx)
- PowerPoint presentations (.pptx)
- Word documents (.docx)
- PDF files
- CSV, JSON, and other data formats
- Source code files in any language
- ZIP archives containing multiple files

### Sessions

The app organizes conversations into sessions:

- **Create a new session**: Tap the + button in the Sessions screen
- **Switch sessions**: Tap a session in the list
- **Pin a session**: Long-press a session and select Pin
- **Delete a session**: Long-press and select Delete
- **Search sessions**: Use the search bar at the top
- **Chat screen**: Shows the current session's messages. The model name is displayed in the center of the header and in the input bar.

### History

The History screen lets you search through all messages across all sessions. Type a keyword in the search bar and matching messages appear with their session name and date.

### Memory

The app can remember information about you across conversations:

- Go to the Memory screen from the drawer
- Add memories manually (e.g., "name: John", "language: Python")
- The AI can auto-extract memories from your conversations
- Each memory has an importance level (1-3 stars)
- Memories are injected into the AI's context automatically

### Templates

Quick-access message templates:

- **@translate**: Translation prompt
- **@summarize**: Summarization prompt
- **@code**: Code explanation prompt
- **@creative**: Creative writing prompt

Tap a template to instantly send it to the chat. Custom templates can be added from the Templates screen.

## Settings

### API Config
- Add, edit, or delete AI providers
- Select active provider
- Configure reasoning mode and effort level (low to max)
- Test connection to verify your provider works

### AI Behavior
- Edit the system prompt (instructions the AI follows)
- Adjust temperature (creativity, 0-2)
- Set context window size (how many past messages the AI remembers)
- Toggle streaming, memory auto-extraction, session auto-naming
- Enable request logging for debugging

### Appearance
- Switch between English and Indonesian
- Choose from 5 themes: Claude Dark, Deep Ocean, Forest Terminal, Clean Light, Crimson
- Adjust font size
- Enable biometric lock (fingerprint/face ID)
- Configure notifications

## Managing Data

### Export Data
Go to Settings and tap "Export All Data" to save all sessions, messages, memories, and settings as a JSON file.

### Delete Data
Go to Settings and tap "Delete All Data" to remove everything. This cannot be undone.

### Clear History
In the History screen, tap the Delete All button to remove all messages while keeping sessions intact.

## Language Support

The app supports English and Indonesian. Change the language in Settings > Appearance > Language.

---

For more information or to report issues, visit the project repository on GitHub.
