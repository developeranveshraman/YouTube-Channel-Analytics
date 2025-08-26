# 🎬 YouTube Channel Analytics

A beautiful, responsive web application that provides detailed analytics for any YouTube channel using the official YouTube Data API v3.

## ✨ Features

- **📊 Comprehensive Analytics**: Get detailed statistics for any YouTube channel
- **🎨 Modern UI**: Beautiful gradient design with smooth animations
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **⚡ Real-time Data**: Fetches live data directly from YouTube's official API
- **🔍 Flexible Search**: Support multiple input formats (URLs, usernames, channel IDs)
- **📈 Key Metrics**: Displays subscriber count, video count, total views, and channel creation date

## 🚀 Demo

Try different channel formats:
- `@MrBeast`
- `https://youtube.com/@MrBeast`
- `UCX6OQ3DkcsbYNE6H8uQQuVA`
- `MrBeast`

## 🛠️ Setup

### Prerequisites

- A web browser
- YouTube Data API v3 key (free from Google Cloud Console)

### Getting Your API Key

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select an existing one
3. Enable the **YouTube Data API v3**
4. Navigate to **Credentials** → **Create Credentials** → **API Key**
5. Copy your API key

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/youtube-channel-analytics.git
cd youtube-channel-analytics
```

2. Open `index.html` in your web browser

3. Enter your YouTube API key in the designated field

4. Start analyzing channels!

## 📖 Usage

### Supported Input Formats

| Format | Example |
|--------|---------|
| Channel URL | `https://youtube.com/@MrBeast` |
| Username with @ | `@MrBeast` |
| Username only | `MrBeast` |
| Channel ID | `UCX6OQ3DkcsbYNE6H8uQQuVA` |
| Custom URL | `https://youtube.com/c/MrBeast` |

### Analytics Provided

- **👥 Subscriber Count**: Total number of subscribers (formatted: 1.2M, 15K, etc.)
- **🎥 Video Count**: Total number of uploaded videos
- **👀 View Count**: Total channel views across all videos
- **📅 Channel Age**: Year the channel was created
- **🖼️ Channel Info**: Profile picture, name, and description

## 🔧 Technical Details

### Built With

- **HTML5** - Structure and semantic markup
- **CSS3** - Modern styling with gradients, animations, and flexbox/grid
- **Vanilla JavaScript** - API calls and DOM manipulation
- **YouTube Data API v3** - Official Google API for YouTube data

### API Endpoints Used

- `GET /youtube/v3/channels` - Channel information and statistics
- `GET /youtube/v3/search` - Channel search by username

### Features

- **Error Handling**: Comprehensive error messages for common issues
- **Loading States**: Visual feedback during API calls
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Performance**: Optimized API calls and efficient DOM updates

## 🎨 Customization

### Color Scheme

The app uses a modern gradient color palette:
- Primary: `#667eea` to `#764ba2`
- Accent: `#ff6b6b` to `#ff8e8e`
- Cards: Various gradient combinations

### Modifying Styles

Key CSS classes for customization:
- `.stat-card` - Individual metric cards
- `.search-section` - Input and search area
- `.results-section` - Analytics display area

## 🔒 Privacy & Security

- **No Data Storage**: The app doesn't store any user data or API keys
- **Client-Side Only**: All processing happens in your browser
- **Official API**: Uses only YouTube's official, approved API endpoints
- **Terms Compliant**: Fully compliant with YouTube's Terms of Service

## 🚫 Limitations

- **API Quotas**: Google provides 10,000 free API calls per day
- **Rate Limiting**: Built-in delays prevent API abuse
- **Public Data Only**: Can only access publicly available channel information
- **No Downloads**: Does not download or cache any video content

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions

- [x] Add video analytics for recent uploads
- [x] Include engagement rate calculations
- [x] Add export functionality for data
- [x] Implement channel comparison features
- [x] Add historical data tracking
- [x] Include social media links extraction

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This tool is for educational and analytical purposes only. It uses YouTube's official API and complies with their Terms of Service. Users are responsible for obtaining their own API keys and using the tool responsibly.

## 🆘 Support

Having issues? Here are common solutions:

### Common Issues

**❌ "API Error" or "Invalid API Key"**
- Verify your API key is correct
- Ensure YouTube Data API v3 is enabled in your Google Cloud project
- Check that your API key has the proper permissions

**❌ "Channel not found"**
- Try different input formats (URL, username, channel ID)
- Ensure the channel exists and is public
- Check for typos in the channel name

**❌ "Quota exceeded"**
- You've reached the daily API limit (10,000 requests)
- Wait until the next day or upgrade your Google Cloud plan

## 📞 Contact

- **GitHub**: [@developeranveshraman](https://github.com/developeranveshraman)
- **Email**: support@anveshraman.rf.gd
- **Issues**: [GitHub Issues](https://github.com/developeranveshraman/YouTube-Channel-Analytics/issues)

---

Made with ❤️ by developeranveshraman | ⭐ Star this repo if you found it helpful!
