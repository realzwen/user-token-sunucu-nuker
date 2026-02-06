# Discord Server Nuker

A powerful Discord server management tool that allows you to quickly delete channels and roles from your Discord servers.

## Features

- Delete all channels in a server
- Delete all roles in a server
- Delete everything (channels + roles)
- Fast and efficient
- User token authentication
- Rate limit handling

## Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/discord-server-nuker.git
cd discord-server-nuker
```

2. Install dependencies
```bash
npm install
```

## Usage

### Windows
Run the `start.bat` file

### Linux/Mac
```bash
node index.js
```

## Getting Your Token

1. Open Discord in your browser (discord.com/app)
2. Press F12 to open Developer Tools
3. Go to the **Network** tab
4. Type "api" in the filter
5. Click on any channel or refresh
6. Click on any request
7. Go to **Headers** section
8. Find **authorization** and copy the value

## Options

After selecting your server, you'll see these options:

1. **Delete all channels** - Removes every channel in the server
2. **Delete all roles** - Removes every role except @everyone
3. **Delete all** - Removes both channels and roles
4. **Exit** - Close the program

## Requirements

- Node.js (v14 or higher)
- npm
- Discord user token

## Important Notes

⚠️ **Warning**: Using user tokens is against Discord's Terms of Service and may result in account termination.

⚠️ **Use at your own risk**: This tool is for educational purposes only.

⚠️ **Irreversible**: Deleted channels and roles cannot be recovered.

## Disclaimer

This tool is provided for educational purposes only. The author is not responsible for any misuse or damage caused by this program. Use it responsibly and only on servers you own or have permission to manage.

## License

Apache License

## Author

Created by zwen

## Support

If you encounter any issues, please open an issue on GitHub.

---

**Note**: This project is not affiliated with Discord Inc.
