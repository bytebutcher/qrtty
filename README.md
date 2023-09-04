<div align="center">

![qrtty Logo](images/qrtty.png)
<h1 align="center" style="margin-top: -50px;">qrtty</h1>

 ![Version: 1.2.0](https://img.shields.io/badge/Version-1.6.0-green)
 [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
</div>
<br/>


**qrtty** generates QR codes directly to the terminal
supporting various types of data like SMS, URLs, Emails, WiFi credentials, vCards, Geolocation, and plain text. 

## Usage

```commandline
Usage: qrtty [OPTION]... [ARGS]...
Generate QR codes directly to the terminal for various types of data.

Types and Parameters:
  sms       [telephone] [message]
  url       [url]
  email     [email] [subject] [body]
  wifi      [ssid] [password] [encryption]
  vcard     [name] [telephone] [email]
  location  [geolocation]
  text      [text]

Prompting:
  If any expected data is missing, you will be prompted to enter it.

Examples:
  qrtty sms +1234567890 'Hello there'
  qrtty email example@email.com 'Subject' 'Email Body'
  qrtty wifi MySSID MyPassword WPA
  qrtty vcard 'John Doe' +1234567890 john@example.com
  qrtty location '40.7128,-74.0060,New York City'
```

## Contributing

Feel free to fork the project and submit a pull request with your changes!

## License

This project is licensed under the GPLv3 License - see the LICENSE.md file for details.