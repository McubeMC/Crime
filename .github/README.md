<div align="center">
  <!-- Introduction -->
  <h1>💫 Crime</h1>
  The most powerful tool that secures our Network.
  <br>
 Crime secure FrameMC and McubeMC servers for your security.
  <br>
<br>
Crime is based on the open-source anti-bot Sonar, huge thanks yo them !

  [Discord](https://mcubemc.fr)
  |
  [License](https://github.com/jonesdevelopment/sonar/?tab=readme-ov-file#license)
  |
  [Documentation](https://docs.jonesdev.xyz/)
</div>

## Design and Goal
* Effective, lightweight, and easy-to-use
* No unnecessary features and clean code
* Protection against all kinds of bot attacks
* No player should be annoyed by any sort of [CAPTCHA](https://en.wikipedia.org/wiki/CAPTCHA)
* No sort of checking for VPNs or proxies
* Multi-platform support (See [supported versions](https://docs.jonesdev.xyz/sonar/supported-versions))

## Checks
Sonar analyzes a player's behavior before joining the actual server, therefore stopping malicious traffic from ever reaching the backend. It is supposed to be an instant, powerful, and simple method of verification that should prevent all typical and advanced types of bots.

1. Sonar sends the player to a lightweight fake server when they connect for the first time.
2. Sonar verifies that players obey the laws of Minecraft's physics, including gravity and proper block collision.
3. Sonar verifies that players send legitimate packets when interacting with vehicles (e.g. boats).
4. Sonar makes sure that players send legitimate packets according to the [vanilla Minecraft protocol](<https://wiki.vg/Protocol>).

Sonar also protects against spambot attacks since it queues the incoming connections, therefore making it technically impossible to have a ton of bots join the server at the same time.

## License
Sonar is licensed under the [GNU General Public License 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

## Credits
- Special thanks to the [contributors of Sonar](https://github.com/jonesdevelopment/sonar/graphs/contributors).
