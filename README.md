# 🤖 AI Interview Platform - Prototype

An intelligent, real-time AI Voice Interview System built using **React**, **Node.js**, and **Vapi AI**. The platform simulates human-like interview experiences using voice-based conversations powered by AI speech recognition (STT), language models (GPT), and text-to-speech (TTS) technologies.

## 🌟 Features

- **Voice-Based Interviews**: Real-time voice interaction powered by Vapi AI
- **AI-Powered Questions**: Intelligent question generation using GPT
- **Speech Recognition**: Accurate speech-to-text (STT) conversion
- **Natural Speech Output**: Text-to-speech (TTS) for AI interviewer responses
- **User Authentication**: Secure login system for candidates
- **Interactive Dashboard**: User-friendly interface to manage interviews
- **Real-Time Feedback**: Instant feedback on candidate responses
- **Interview History**: Track completed interviews and performance
- **Responsive Design**: Works seamlessly across devices

## 🛠️ Technology Stack

### Frontend
- **React.js** - User interface and interactions
- **HTML5** - Markup structure
- **CSS3** - Styling and responsiveness
- **JavaScript** - Client-side logic

### Backend
- **Node.js** - Server-side runtime
- **Express.js** - API framework (implied)
- **Vapi AI** - Voice and AI integration

### AI/ML Components
- **Vapi AI** - Voice AI integration
- **GPT** - Language model for question generation
- **Speech-to-Text (STT)** - Audio input processing
- **Text-to-Speech (TTS)** - Audio output generation

## 📁 Project Structure

```
AI_interview_platform/
├── login.html                          # User login page
├── dasboard.html                       # User dashboard
├── interview.html                      # Interview start page
├── interviewPage.html                  # Main interview interface
├── final.html                          # Results and analysis page
├── feedback.html                       # Feedback and performance review
├── confirmation.html                   # Confirmation page
├── AI interview website Flowchart.png  # System architecture diagram
├── Screenshot 2025-11-22 *.png        # UI screenshots
└── README.md                           # This file
```

## 📋 Page Descriptions

| Page | Purpose |
|------|---------|
| **login.html** | User authentication and account access |
| **dasboard.html** | Main dashboard showing interview history and options |
| **interview.html** | Interview setup and configuration |
| **interviewPage.html** | Live interview interface with voice interaction |
| **final.html** | Comprehensive results and performance analysis |
| **feedback.html** | Detailed feedback on responses and improvements |
| **confirmation.html** | Interview completion confirmation |

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Vapi AI API Key
- OpenAI API Key (for GPT integration)
- Modern web browser with microphone access

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ravisingh-6386/AI_interview_platform-Prototype-of-website-.git
   cd AI_interview_platform-Prototype-of-website-
   ```

2. **Install backend dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory:
   ```env
   VAPI_API_KEY=your_vapi_api_key
   OPENAI_API_KEY=your_openai_api_key
   NODE_ENV=development
   PORT=5000
   ```

4. **Start the server:**
   ```bash
   npm start
   ```

5. **Access the application:**
   Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

## 🎯 User Flow

```
User Login
    ↓
Dashboard
    ↓
Start Interview
    ↓
Interview Configuration
    ↓
Live Interview (Voice Interaction)
    ↓
Results & Analysis
    ↓
Detailed Feedback
    ↓
Confirmation
```

## 🎤 Interview Process

1. **Authentication**: User logs in with credentials
2. **Setup**: Configure interview type and job role
3. **Voice Interaction**: Real-time conversation with AI interviewer
4. **Speech Processing**: User responses captured via STT
5. **AI Analysis**: GPT analyzes responses for quality and relevance
6. **Feedback Generation**: TTS delivers personalized feedback
7. **Results**: Comprehensive performance report displayed
8. **History**: Interview saved to user's dashboard

## 🔧 Key Features Details

### Real-Time Voice Processing
- Captures audio input from user's microphone
- Converts speech to text using STT
- Processes responses through language model
- Generates and speaks responses using TTS

### AI-Powered Intelligence
- Context-aware question generation
- Response evaluation and scoring
- Personalized feedback based on performance
- Adaptive question difficulty

### User Experience
- Intuitive navigation between pages
- Real-time status indicators
- Progress tracking
- Mobile-responsive design

## 📊 System Architecture

See `AI interview website Flowchart.png` for detailed system architecture and data flow.

## 🔐 Security Features

- Secure user authentication
- API key management
- CORS configuration
- Input validation
- Secure data transmission

## 🐛 Troubleshooting

### Microphone Access
- Grant microphone permissions in browser settings
- Check browser compatibility (Chrome, Firefox, Safari, Edge)
- Ensure HTTPS connection (required for microphone access)

### API Issues
- Verify Vapi AI API key is valid
- Check OpenAI API key configuration
- Ensure API rate limits are not exceeded
- Review server logs for errors

### Performance
- Clear browser cache if experiencing issues
- Update to latest browser version
- Check internet connection stability
- Review server resource usage

## 📝 Development

### Running in Development Mode
```bash
npm run dev
```

### Building for Production
```bash
npm run build
```

### Testing
```bash
npm test
```

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs and issues
- Suggest new features
- Submit pull requests
- Improve documentation
- Share feedback

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License. See LICENSE file for details.

## 👤 Author

**Ravi Singh** (@ravisingh-6386)

## 📞 Support & Contact

For questions, issues, or suggestions:
- Open an issue on GitHub
- Check existing issues for solutions
- Review the project documentation
- Contact the maintainer

## 🎓 Learning Resources

- [Vapi AI Documentation](https://docs.vapi.ai)
- [OpenAI API Documentation](https://platform.openai.com/docs)
- [React Documentation](https://react.dev)
- [Node.js Documentation](https://nodejs.org/docs)

## 🔮 Future Enhancements

- [ ] Multiple language support
- [ ] Advanced analytics dashboard
- [ ] Interview recording and playback
- [ ] Custom question sets
- [ ] Performance benchmarking
- [ ] Team collaboration features
- [ ] Mobile app version
- [ ] Video interview capabilities

## 📈 Project Status

**Status**: Active Development (Prototype)

**Last Updated**: March 4, 2026

---

**Made with ❤️ by Ravi Singh**

[GitHub Repository](https://github.com/ravisingh-6386/AI_interview_platform-Prototype-of-website-)
