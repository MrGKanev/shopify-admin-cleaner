# Shopify Admin Cleaner v1

A robust bookmarklet that helps clean up the Shopify admin interface by hiding redundant details. This tool helps you show/print only the information you need, with built-in safety features and error handling.

## Features

- One-click activation/deactivation
- No installation required
- Works with all modern browsers
- Zero dependencies

## Installation

1. Visit the tool's webpage
2. Drag the green "🧹 Toggle Details" button to your browser's bookmarks bar
3. Navigate to your Shopify admin orders page
4. Click the bookmark to toggle the cleaner

## How It Works

The bookmarklet injects a small CSS rule that toggles visibility of paragraphs containing subdued text (`.Polaris-Text--subdued`). Key technical features:

- Uses a data attribute to track style injection
- Implements rate limiting to prevent rapid activation
- Validates the current URL to ensure it's a Shopify admin page
- Checks for browser compatibility before execution
- Provides console feedback for debugging

## Security Features

- URL validation prevents execution on non-Shopify pages
- Error handling with user-friendly alerts
- Rate limiting prevents accidental multiple activations
- Safe style injection with proper attribute tracking
- Console logging for troubleshooting

## Troubleshooting

### Common Issues

1. **Bookmark Not Working**
   - Verify you're on a Shopify admin page
   - Check if your browser is up to date
   - Try refreshing the page
   - Ensure JavaScript is enabled

2. **Details Not Hiding**
   - Confirm you're using the latest version
   - Check console for error messages
   - Verify Shopify hasn't updated their UI structure

3. **Rate Limiting Message**
   - Wait one second between clicks
   - Refresh the page if the cooldown persists

### Browser Support

- Chrome 49+
- Firefox 51+
- Safari 10+
- Edge 79+
- Opera 36+

## Use Cases

1. **Order Processing**
   - Clean interface for rapid order processing
   - Reduced visual clutter for better focus
   - Improved efficiency in high-volume scenarios

2. **Documentation**
   - Clean screenshots for training materials
   - Simplified interface for documentation
   - Better visual hierarchy in prints

3. **Training**
   - Simplified interface for new staff
   - Focus on essential information
   - Reduced cognitive load during learning

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Development

### Local Testing

```bash
# Clone the repository
git clone https://github.com/yourusername/shopify-admin-cleaner
cd shopify-admin-cleaner

# Open index.html in your browser
# Test changes on a Shopify development store
```


## Author

Created by [Gabriel Kanev](https://gkanev.com)

## License

This project is available under the MIT License. See the LICENSE file for details.

## Support

For support, please:

1. Check the troubleshooting guide
2. Search existing issues
3. Create a new issue if needed


Made with ❤️ for the Shopify community
