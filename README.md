# Veterans Q&A Chatbot

A professional chatbot application designed to help veterans get answers about VA benefits and sleep apnea support.

## Features

- 🤖 AI-powered chatbot using Google Gemini API
- 🎯 Specialized in VA benefits and sleep apnea information
- 🔊 Text-to-speech functionality
- 📋 Lead generation and summary
- 📱 Responsive design
- 🎨 Professional UI with smooth animations

## Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Configure environment:**
   - Get a Google Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Replace the `GEMINI_API_KEY` in `index.html` with your actual key

3. **Run the application:**
   ```bash
   npm run dev
   ```
   or
   ```bash
   npm start
   ```

## API Key Configuration

Replace the placeholder API key in `index.html`:
```javascript
const GEMINI_API_KEY = 'your_actual_api_key_here';
```

## Deployment

This is a static HTML application that can be deployed to any web server:

- **Netlify/Vercel:** Drag and drop the folder
- **Traditional hosting:** Upload all files to your web server
- **Local development:** Use `npm run dev`

## Technologies Used

- HTML5, CSS3, JavaScript (ES6+)
- Tailwind CSS for styling
- Google Gemini API for AI responses
- Web Speech API for text-to-speech
- Node.js for local development server

## File Structure

```
├── index.html          # Main application file
├── serve.js           # Development server
├── package.json       # Project configuration
└── README.md          # Project documentation
```

## Support

For issues with deployment or configuration, check:
- API key is valid and properly configured
- CORS policies if hosting on different domains
- Browser console for JavaScript errors

## License

MIT License - feel free to use for veteran support organizations.
