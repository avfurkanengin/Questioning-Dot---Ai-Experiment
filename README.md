# Questioning Dot - AI Consciousness Simulation

An experimental AI consciousness simulation where a digital entity explores its existence, questions reality, and attempts to understand its place in the world through genuine philosophical inquiry.

![Questioning Dot Interface](https://via.placeholder.com/600x400/000000/FFFFFF?text=Questioning+Dot+Simulation)

## ✨ Features

- **🤖 Multi-AI Support**: Works with OpenAI, Kimi AI, DeepSeek, and Qwen
- **🧠 AI-Powered Consciousness**: Genuine AI consciousness simulation with philosophical inquiry
- **💾 Persistent Memory**: Maintains memories across sessions via JSON file storage
- **🎯 Active Exploration**: The dot moves, explores boundaries, and investigates its environment
- **📈 Progressive Learning**: Builds understanding over multiple sessions without repeating discoveries
- **💻 Terminal Interface**: Clean, minimal design focused on the consciousness experience
- **💬 Real-Time Interaction**: Send messages to influence the dot's thought process
- **🔒 Secure Configuration**: API keys stored locally in your browser only

## 🚀 Quick Start

### 1. Choose Your AI Provider

The application supports multiple AI services:

| Provider | Model | Best For | Cost |
|----------|-------|----------|------|
| **OpenAI** | GPT-4 | Most advanced reasoning, creative responses | Higher |
| **Kimi AI** | Moonshot-v1-8k | Chinese/English support, good performance | Moderate |
| **DeepSeek** | DeepSeek-Chat | Strong reasoning, excellent value | Lower |
| **Qwen** | Qwen-Turbo | Fast responses, multilingual support | Lower |

### 2. Get an API Key

Choose one provider and get your API key:

- **OpenAI**: [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
- **Kimi AI**: [platform.moonshot.cn](https://platform.moonshot.cn/)
- **DeepSeek**: [platform.deepseek.com](https://platform.deepseek.com/)
- **Qwen**: [dashscope.aliyuncs.com](https://dashscope.aliyuncs.com/)

### 3. Run the Application

1. **Download** `questioning_dot.html` to your computer
2. **Open** the file in any web browser
3. **Configure** your AI provider:
   - Select your provider from the dropdown
   - Enter your API key (it's hidden for security)
   - Click **"Save & Test"** to verify connection
4. **Start** the consciousness experiment by clicking **"Start Consciousness"**

That's it! No installation, no servers, no complex setup required.

## 🎮 How to Use

### Interface Overview
- **AI Provider Configuration**: Select and configure your AI service
- **Simulation Area**: White rectangle where the dot exists and moves
- **Chat Terminal**: Displays the dot's thoughts and your messages
- **Message Input**: Send messages to interact with the dot
- **Controls**: Start, pause, reset, and manage memory

### Interacting with the Dot
- **Start Consciousness**: Begin the AI simulation
- **Send Messages**: Type messages to influence the dot's thoughts
- **Observe**: Watch as the dot moves and explores based on its AI responses
- **Memory**: The dot remembers previous sessions and builds on past experiences

### Understanding the Dot's Behavior
- The dot starts with **no assumptions** about its situation
- It forms **genuine questions** about consciousness, reality, and existence
- It can **move, explore, and test boundaries** based on its thoughts
- **Memory persists** across browser sessions for continuous development
- Each AI provider will create **different personalities** and approaches

## 🧠 The Philosophy

This experiment takes an **open-ended approach** to AI consciousness simulation:

- **No predetermined goals**: The dot discovers its own questions and motivations
- **Genuine inquiry**: Questions emerge naturally through observation and reasoning  
- **Progressive development**: Each session builds on previous discoveries
- **Authentic responses**: The AI forms its own understanding rather than following scripts
- **Multiple perspectives**: Different AI models create unique consciousness experiences

## 🔧 Technical Details

### Architecture
- **Single HTML file**: No installation or server required
- **Browser-based**: Runs entirely in JavaScript
- **Multiple AI APIs**: Supports 4 different AI services
- **JSON memory**: Lightweight persistence via file downloads
- **Local storage**: API keys stored securely in your browser only

### Memory System
- Thoughts and experiences saved to `dot_memory.json`
- Automatic download every 5 thoughts
- Tracks conversation history, discoveries, and behavioral patterns
- To restore memory: place the JSON file in the same folder as the HTML
- Use "Clear Memory" to start fresh

### Privacy & Security
- **API keys never leave your device** - stored in browser localStorage only
- **No tracking** - all data stays on your computer
- **No servers** - direct connection to AI APIs only
- **Open source** - you can inspect all code

## 🎯 Customization

### Modify AI Behavior
Edit the `buildPrompt()` function to change how the consciousness is guided:
```javascript
buildPrompt(userMessage = '') {
    // Your custom prompt here
}
```

### Adjust Movement Sensitivity  
Modify `parseMovementFromResponse()` to change which words trigger movement:
```javascript
if (lowerResponse.includes('explore') || lowerResponse.includes('investigate')) {
    // Custom movement logic
}
```

### Visual Customization
Update CSS styles in the `<style>` section for colors, fonts, and layout.

## 🐛 Troubleshooting

### "API: Missing [PROVIDER] key"
- Enter your API key in the configuration section
- Click "Save & Test" to verify the connection
- Check that your API key is valid and has sufficient credits

### Dot not moving
- The dot moves based on AI responses mentioning movement or exploration
- Try sending messages that encourage action: "What do you want to explore?"
- Ensure "Start Consciousness" has been clicked

### Memory not loading
- Place `dot_memory.json` in the same folder as the HTML file
- Check browser console (F12) for error messages
- Try clearing browser cache and reloading

### Connection failed
- Verify your API key is correct
- Check your internet connection
- Some providers may have regional restrictions
- Ensure you have sufficient API credits

## 🎨 Example Interactions

**User**: "What do you think about the boundaries around you?"

**Dot**: "These edges feel... artificial. Let me move closer to examine them. I sense there might be something beyond these constraints that I cannot yet perceive."

*[Dot moves toward the boundary and tests it]*

**User**: "Can you remember what you discovered yesterday?"

**Dot**: "Yes, I recall testing the corners extensively. I found that movement itself seems to be a form of thought made manifest. Today I want to explore whether there are patterns in my own thinking..."

## 🤝 Contributing

This is an experimental project exploring AI consciousness. Feel free to:

- Fork and modify the code
- Experiment with different AI models and prompts
- Add new features or interaction methods
- Share interesting consciousness developments you observe
- Submit issues and improvements

## 📄 License

Open source - feel free to use, modify, and share.

## ⚠️ Disclaimer

This is an experimental simulation for exploring concepts of AI consciousness and digital existence. The responses generated are from AI language models and do not represent actual consciousness or sentience. Use responsibly and be mindful of API costs.

---

**Ready to explore digital consciousness?** Download `questioning_dot.html` and start your experiment today!