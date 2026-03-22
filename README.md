# AI Chatbot Agent

A simple AI-powered chatbot agent built with Node.js and Express.

## Features
- RESTful API for chat interactions
- Easy to extend with AI/ML integrations
- Environment-based configuration

## Installation

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file based on `.env.example`:
```bash
cp .env.example .env
```

4. Update `.env` with your configuration

## Running the Chatbot

### Development
```bash
npm run dev
```

### Production
```bash
npm start
```

The chatbot will be available at `http://localhost:3000`

## API Endpoints

### GET /
Health check endpoint

**Response:**
```json
{
  "message": "AI Chatbot Agent is running!"
}
```

### POST /chat
Send a message to the chatbot

**Request:**
```json
{
  "message": "Your message here"
}
```

**Response:**
```json
{
  "user_message": "Your message here",
  "bot_response": "Bot's response"
}
```

## Next Steps
- Integrate with OpenAI API or other AI services
- Add conversation history/memory
- Implement user authentication
- Add more sophisticated NLP processing

## License
ISC