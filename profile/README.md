<div align="center">
    <img alt="Tinyauth" title="Tinyauth" width="96" src="https://github.com/tinyauthapp/tinyauth/raw/main/assets/logo-rounded.png">
    <h1>Tinyauth</h1>
    <p>The tiniest OpenID Certified™ authorization and authentication server you have ever seen.</p>
</div>

<div align="center">
    <img alt="License" src="https://img.shields.io/github/license/tinyauthapp/tinyauth">
    <img alt="Release" src="https://img.shields.io/github/v/release/tinyauthapp/tinyauth">
    <img alt="Issues" src="https://img.shields.io/github/issues/tinyauthapp/tinyauth">
    <img alt="Tinyauth CI" src="https://github.com/tinyauthapp/tinyauth/actions/workflows/ci.yml/badge.svg">
    <a title="Crowdin" target="_blank" href="https://crowdin.com/project/tinyauth"><img src="https://badges.crowdin.net/tinyauth/localized.svg"></a>
    <a href="https://scorecard.dev/viewer/?uri=github.com/tinyauthapp/tinyauth" target="_blank" title="OpenSSF Scorecard">
      <img src="https://api.scorecard.dev/projects/github.com/tinyauthapp/tinyauth/badge">
    </a>
    <a href="https://www.bestpractices.dev/projects/12681" target="_blank" title="OSSF Best Practices"><img src="https://www.bestpractices.dev/projects/12681/baseline"></a>
</div>

<br />

Tinyauth is the simplest and tiniest authentication and authorization server you have ever seen. It is designed to both work as an authentication middleware for your apps, offering support for OAuth, LDAP and access-controls, and as a standalone authentication server. It supports all the popular proxies like Traefik, Nginx and Caddy.

![Screenshot](https://github.com/tinyauthapp/tinyauth/raw/main/assets/screenshot.png)

As of 2026-06-25, Tinyauth v5.1.0 is OpenID Certified™ for Basic OP. You can find the certification details [here](https://openid.net/certification-old/certified-openid-providers-profiles/), test suite available [here](https://www.certification.openid.net/plan-detail.html?public=true&plan=H0qhpsOcQkxUE).

<img alt="OpenID Certified" width="200" src="https://openid.net/wordpress-content/uploads/2016/05/oid-l-certification-mark-l-cmyk-150dpi-90mm.jpg" />

## Getting Started

You can get started with Tinyauth by following the guide in the [documentation](https://tinyauth.app/docs/getting-started). There is also an available [docker-compose](./docker-compose.example.yml) file that has Traefik, Whoami and Tinyauth to demonstrate its capabilities (keep in mind that this file lives in the development branch so it may have updates that are not yet released).

## Demo

If you are still not sure if Tinyauth suits your needs you can try out the [demo](https://demo.tinyauth.app). The default username is `user` and the default password is `password`.

## Documentation

You can find documentation and guides on all of the available configuration of Tinyauth in the [website](https://tinyauth.app).

If you wish to contribute to the documentation head over to the [repository](https://github.com/tinyauthapp/docs).

## Discord

Tinyauth has a [Discord](https://discord.gg/eHzVaCzRRd) server. Feel free to hop in to chat about self-hosting, homelabs and of course Tinyauth. See you there!

## License

Tinyauth is licensed under the GNU Affero General Public License v3.0. TL;DR — You may copy, distribute and modify the software as long as you track changes/dates in source files. Any modifications to or software including (via compiler) AGPL-licensed code must also be made available under the AGPL along with build & install instructions. If you run a modified version over a network, you must also make the source available to the users of that service. For more information about the license check the [license](LICENSE) file.


