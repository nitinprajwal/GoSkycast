# 🌦️ GoSkycast: Your Weather Companion in the Terminal

[![Go Version](https://img.shields.io/badge/Go-1.16+-00ADD8?style=flat-square&logo=go)](https://golang.org)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

GoSkycast is a powerful and user-friendly Command Line Interface (CLI) tool that brings real-time weather information to your fingertips, right in your terminal. Written in Go, it provides instant access to current temperatures and multi-day forecasts for any location worldwide.

## 🚀 Features

- 🌡️ Get current temperature for any location
- 🔮 Fetch weather forecasts for up to 3 days
- 🌍 Support for global locations
- ⚡ Lightning-fast performance
- 🧩 Simple and intuitive command structure

## 🛠️ Installation

### Prerequisites

- Go 1.16 or higher
- An API key from [weatherapi.com](https://www.weatherapi.com/)

### Steps

1. Install GoSkycast using Go:

   ```bash
   go get -u github.com/nitinprajwal/GoSkycast
   ```

2. Set up your API key as an environment variable:

   ```bash
   export WeatherApiKey="your_api_key_here"
   ```

   For permanent setup, add this line to your `.bashrc` or `.zshrc` file.

## 🎮 Usage

The basic command structure is:

```bash
goskycast [flags] [location]
```

### Flags

| Flag | Description |
|------|-------------|
| `--help` or `-h` | Display help information |
| `--temp` or `-t` | Get current temperature only |
| `--forecast` or `-f` | Get weather forecast (up to 3 days) |

## 📚 Examples

1. Get current temperature for New York:

   ```bash
   goskycast -t "New York"
   ```

2. Fetch a 2-day forecast for London:

   ```bash
   goskycast -f=2 London
   ```

3. Display help information:

   ```bash
   goskycast --help
   ```

## 🤝 Contributing

We welcome contributions to GoSkycast! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgements

- [weatherapi.com](https://www.weatherapi.com/) for providing the weather data API
- The Go community for their invaluable resources and support

---

<p align="center">
  Made with ❤️ by NITIN PRAJWAL R
</p>