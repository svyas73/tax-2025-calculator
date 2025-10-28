# Tax Planning Calculator 2025

A comprehensive web-based tax planning calculator focused on solar investment and charitable donation strategies for tax year 2025.

## Features

- **Solar Investment Analysis**: Calculate tax benefits of solar investments with federal and California state tax considerations
- **Charitable Donation Optimization**: Maximize deductions while minimizing actual cash outlay
- **Progressive Tax Calculations**: Accurate 2025 federal and California tax bracket calculations
- **Interactive Comparison Table**: Compare different solar investment amounts ($50K - $500K)
- **Export Capabilities**: Download results as PDF or Excel/CSV files
- **Responsive Design**: Works on desktop and mobile devices

## Key Tax Strategies

1. **Solar Tax Credit**: Federal credit equal to solar investment amount
2. **Accelerated Depreciation**: Federal depreciation benefits with revenue timing options
3. **California Depreciation**: Straight-line depreciation on total assets (2.5x solar investment)
4. **Charitable Deductions**: Up to 60% of reduced AGI with 20% actual payment requirement

## Usage

1. Open `index.html` in your web browser
2. Enter your financial parameters:
   - Filing status
   - Annual gross income
   - Solar investment amount
   - Solar revenue timing
   - Maintenance rate
   - Donation percentage
3. View detailed tax calculations and comparisons
4. Export results for further analysis

## Technical Details

- **Frontend**: Pure HTML, CSS, and JavaScript
- **Tax Brackets**: 2025 federal and California tax brackets
- **Calculations**: Progressive tax system with proper bracket handling
- **Export**: Client-side PDF generation and CSV download

## Development

### Local Development Server

```bash
# Using Python (recommended)
python -m http.server 8000

# Using Node.js (if you have it installed)
npx http-server -p 8000
```

Then open `http://localhost:8000/index.html` in your browser.

### VS Code Configuration

The project includes VS Code configuration for:
- Chrome debugging
- Live server integration
- HTML/CSS/JavaScript IntelliSense

## License

MIT License - see LICENSE file for details

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## Disclaimer

This calculator is for educational and planning purposes only. Always consult with a qualified tax professional for actual tax planning decisions.
