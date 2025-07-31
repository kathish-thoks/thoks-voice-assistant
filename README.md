# THOKS - Advanced Voice Assistant

A sci-fi themed voice assistant built with React, Next.js, and AI APIs. Features wake word detection, voice input/output, AI chat, and web search capabilities.

## Features

- 🎤 **Wake Word Detection**: Say "Thoks" to activate the assistant
- 🗣️ **Voice Input**: Uses Web Speech API for speech recognition
- 🤖 **AI Chat**: Powered by OpenAI GPT-4 Mini for intelligent responses
- 🔊 **Voice Output**: Realistic voice synthesis using ElevenLabs API
- 🔍 **Web Search**: Live search results integration
- 🎨 **Sci-Fi UI**: Animated neon interface with glowing effects

## Environment Variables

Create a \`.env.local\` file with the following variables:

\`\`\`
OPENAI_API_KEY=your_openai_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
SEARCH_API_KEY=your_search_api_key
\`\`\`

## Getting Started

1. Install dependencies:
\`\`\`bash
npm install
\`\`\`

2. Set up environment variables (see above)

3. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Usage

1. **Activation**: Say "Thoks" to wake up the assistant
2. **Voice Input**: Speak your question or command
3. **AI Response**: THOKS will process and respond with voice + text
4. **Search**: Include words like "search", "find", or "look up" for web searches
5. **Reset**: Click "NEW SESSION" to start over

## Browser Requirements

- Modern browser with Web Speech API support (Chrome, Edge, Safari)
- Microphone access permissions
- HTTPS connection (required for speech recognition)

## API Integrations

- **OpenAI GPT-4 Mini**: Conversational AI responses
- **ElevenLabs**: High-quality voice synthesis
- **Search API**: Web search functionality (SearchAPI.com or similar)

## Tech Stack

- **Frontend**: Next.js 14, React, Tailwind CSS
- **Voice**: Web Speech API, ElevenLabs API
- **AI**: OpenAI GPT-4 Mini via AI SDK
- **Search**: Search API integration
- **Styling**: Tailwind CSS with custom sci-fi theme
\`\`\`
