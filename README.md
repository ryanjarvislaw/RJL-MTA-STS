<h1 align="center">
  <br>
  📩 MTA-STS Policy File for Ryan Jarvis Law®
  <br>
</h1>
</p>

MTA-STS is a security standard to secure e-mail delivery. E-mail servers that send inbound e-mail to our domain will be able to detect that our e-mail server supports SMTP-over-TLS via `STARTTLS` (also known as [Opportunistic TLS](https://en.wikipedia.org/wiki/Opportunistic_TLS)) before opening the actual connection.

In case the sending e-mail server is not able to initiate a secure connection, it will end the connection to enforce transport layer encryption. This mitigates [Man-in-the-middle](https://en.wikipedia.org/wiki/Man-in-the-middle_attack) DNS and SMTP [downgrade attacks](https://en.wikipedia.org/wiki/Downgrade_attack) that would allow an attacker to read or manipulate e-mail in transit.

## License

[MIT License](https://github.com/ryanjarvislaw/mta-sts/blob/gh-pages/LICENSE)

## Author

[www.ryanjarvis.law](https://www.ryanjarvis.law/) &nbsp;&middot;&nbsp;
GitHub [@ryanjarvislaw](https://github.com/ryanjarvislaw/mta-sts) &nbsp;&middot;&nbsp;
