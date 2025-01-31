# Swedish Electricity Prices Dashboard

A real-time dashboard showing electricity prices across different regions in Sweden. Data is sourced from [elprisetjustnu.se](https://www.elprisetjustnu.se).

## Features

- Real-time electricity prices for all Swedish regions (SE1, SE2, SE3, SE4)
- Interactive price chart using Chart.js
- Detailed price table for the current day
- Automatic updates every 5 minutes
- Responsive design for mobile and desktop

## Development Setup

1. Clone this repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

2. For local development, you can use any of these methods:

### Using Python's built-in server
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

### Using Node.js's http-server
First install http-server:
```bash
npm install -g http-server
```
Then run:
```bash
http-server
```
Visit `http://localhost:8080` in your browser.

### Using Visual Studio Code
Install the "Live Server" extension and click "Go Live" in the bottom right corner.

## Deployment to GitHub Pages

1. Create a new repository on GitHub

2. Initialize git and push your code:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <your-repository-url>
git push -u origin main
```

3. Go to your repository settings on GitHub
4. Scroll down to "GitHub Pages" section
5. Select the branch you want to deploy (usually `main`)
6. Select the root folder as the source
7. Save the settings

Your site will be available at `https://<your-username>.github.io/<repository-name>/`

## Development Tips

- The site uses vanilla JavaScript, HTML, and CSS - no build process required
- CORS is handled by the API, so no proxy is needed
- Use the browser's developer tools (F12) to debug any issues
- The Chart.js library is loaded from CDN for simplicity

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Data provided by [elprisetjustnu.se](https://www.elprisetjustnu.se)
- Charts powered by [Chart.js](https://www.chartjs.org/) 