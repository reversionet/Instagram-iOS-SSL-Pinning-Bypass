# Instagram iOS SSL Pinning Bypass

A patched version of Instagram for iOS with SSL/TLS certificate pinning disabled, allowing HTTPS traffic inspection for security research, reverse engineering, and mobile application analysis.

This repository is maintained and updated regularly with support for newer Instagram releases.

## Features

* No jailbreak required
* No Frida required
* SSL/TLS certificate pinning removed
* Supports HTTPS traffic interception through a proxy
* iOS compatible

## About SSL Pinning

SSL pinning (also known as certificate pinning) is a security mechanism that prevents applications from trusting certificates outside a predefined set. This repository demonstrates how SSL pinning can be removed through binary patching for research and educational purposes.

Read more:

https://yinsolutions.org/blogs/how-to-bypass-certificate-pinning-ig.html

## Information

* Latest patched version: **395.0.0**
* Platform: **iOS**
* Tested on: **iOS 15.4.1**
* HTTPS requests can be inspected using a supported proxy
* Community feedback is appreciated

## Installation

1. Download the IPA file below.
2. Install it using:

   * Sideloadly
   * TrollStore
3. Configure your HTTPS interception proxy before launching the application.
4. Launch Instagram and begin inspecting traffic.

### Supported Proxies

* mitmproxy (tested)
* Burp Suite
* Charles Proxy
* Proxyman

## Known Issues

### Application Crashes After Login

Some users have reported crashes after signing in when using certain sideloading methods.

**Recommended solution:** Install the IPA using TrollStore. This has proven to be the most reliable method for avoiding post-login crashes.

## Available Release

| App       | Bundle ID           | Version | File Type | Download                                                                                                            |
| --------- | ------------------- | ------- | --------- | ------------------------------------------------------------------------------------------------------------------- |
| Instagram | com.burbn.instagram | 395.0.0 | IPA       | [Download](https://github.com/reversionet/Instagram-iOS-SSL-Pinning-Bypass/releases/download/v395/Instagram395.ipa) |

## Other Apps

Additional bypassed applications may be available. Check my repositories for current releases and updates.

## SSL Pinning & Jailbreak Detection Training

Interested in learning how SSL pinning bypasses, jailbreak detection bypasses, and mobile application patching work?

Training and private courses/custom apps are available.

**Telegram:** [@reversio1](https://t.me/reversio1)

Custom application requests may also be available.

## Disclaimer

This project is provided strictly for educational, research, and testing purposes.

The purpose of this repository is to help security researchers, developers, and reverse engineers better understand SSL/TLS certificate pinning and mobile application security mechanisms.

Users are solely responsible for ensuring their activities comply with applicable laws, regulations, and terms of service. The author assumes no responsibility for misuse, damages, or legal consequences resulting from the use of this project.

If you have any concerns regarding this repository, please contact:

**[disclaimer@reversio.net](mailto:disclaimer@reversio.net)**
