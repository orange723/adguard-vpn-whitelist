# adguard-vpn-whitelist

This project provides a whitelist of Chinese websites for AdGuard VPN, allowing users to bypass the VPN for commonly used domestic sites.

## Features

- Regularly updated whitelist of Chinese domains.
- Automatically synced to a GitHub Gist via GitHub Actions for easy access and integration.

## Usage

1. Download the `whitelist.txt` file from [this repository](./whitelist.txt) or from the [Gist mirror](https://gist.github.com/orange723/91b39676071eec9d5b2cf8f2707b499e).
2. Import the whitelist into AdGuard VPN according to the official instructions.

## Contributing

Contributions are welcome! To add or update domains in the whitelist:

1. Fork this repository.
2. Edit `whitelist.txt` (one domain per line, comments start with `#`).
3. Submit a pull request.

## Format Guidelines

- One domain per line (e.g., `baidu.com`).
- Lines starting with `#` are treated as comments.

## Automation

This repository uses GitHub Actions to automatically update the whitelist file to a designated GitHub Gist after each commit.

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.