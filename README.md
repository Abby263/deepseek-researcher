# DeepSearch - AI-Powered Content Research Assistant

DeepSearch is an advanced content research assistant that combines the power of AI with real-time web search capabilities to help content creators, researchers, and professionals gather and analyze information efficiently.

## 🚀 Features

### Core Functionality
- **Real-time Web Search**: Integrates with Tavily API for comprehensive web search results
- **AI-Powered Analysis**: Uses Deepseek AI to analyze search results and provide detailed reports
- **Interactive Chat Interface**: Maintains conversation history for contextual responses
- **Streaming Responses**: Real-time streaming of AI analysis and thinking process
- **Rich Media Support**: Displays images and visual content from search results
- **Source Attribution**: Automatic citation and source linking in reports

### User Experience
- **Content Templates**: Pre-built templates for common content types:
  - Podcast Outlines
  - YouTube Video Research
  - Short Form Hook Ideas
  - Newsletter Drafts
- **Visual Feedback**:
  - Loading states with progress indicators
  - Animated transitions
  - Collapsible sections for thinking process
- **Responsive Design**: Works seamlessly on desktop and mobile devices

### Advanced Features
- **Source Verification**: View and verify original sources
- **Thinking Process**: Transparent AI reasoning process
- **Full Data Access**: Access to complete search data and AI reasoning
- **Markdown Support**: Rich text formatting in responses
- **Error Handling**: Comprehensive error handling and user feedback

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animation**: Framer Motion
- **Markdown**: React Markdown with remark-gfm

### Backend
- **Runtime**: Edge Runtime
- **APIs**:
  - Tavily API (Web Search)
  - Deepseek API (AI Analysis)

### Development
- **Package Manager**: npm/yarn
- **Type Checking**: TypeScript
- **Code Quality**: ESLint

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd deepseek-researcher
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file with:
   ```env
   DEEPSEEK_API_KEY=your_deepseek_api_key
   TAVILY_API_KEY=your_tavily_api_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

## 🔧 Configuration

### API Keys
- **Deepseek**: Get your API key from [Deepseek's platform](https://deepseek.ai)
- **Tavily**: Get your API key from [Tavily's platform](https://tavily.com)

### Environment Variables
- `DEEPSEEK_API_KEY`: Your Deepseek API key
- `TAVILY_API_KEY`: Your Tavily API key

## 🎯 Usage

1. **Start Research**:
   - Enter your research query in the main input field
   - Optionally select a content template for specific formats

2. **View Results**:
   - See real-time search results with images
   - Watch the AI's thinking process
   - Read the comprehensive analysis

3. **Interact**:
   - Ask follow-up questions
   - View source materials
   - Explore the AI's reasoning

4. **Export**:
   - Copy formatted text
   - Click source links for original content
   - View full data exports

## 🔄 Development Workflow

1. **Local Development**:
   ```bash
   npm run dev
   ```

2. **Build**:
   ```bash
   npm run build
   ```

3. **Production**:
   ```bash
   npm start
   ```

## 📝 TODO

### Immediate Priorities
- [ ] Add export functionality for research results
- [ ] Implement save/bookmark feature for searches
- [ ] Add user history and saved searches
- [ ] Enhance error handling for API failures
- [ ] Add authentication system

### Future Enhancements
- [ ] Add more content templates
- [ ] Implement collaborative research features
- [ ] Add custom styling options for exports
- [ ] Integrate with more research APIs
- [ ] Add PDF export functionality
- [ ] Implement team sharing features

### Performance Improvements
- [ ] Optimize image loading and caching
- [ ] Implement better search result pagination
- [ ] Add offline support for saved searches
- [ ] Optimize API response caching

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Deepseek for AI capabilities
- Tavily for search API
- Next.js team for the amazing framework
- All contributors and users of the application