<p align="center">
	<img src="/dev/wg-dashboard-logo.png" />
</p>

# wg-dashboard

![Dashboard](dev/dashboard.png)

## Description

#### What is this?

wg-dashboard is a user friendly and easy to use interface to manage your WireGuard instance and peers.

#### Why did we make this?

We made this dashboard to simplify the setup of WireGuard. Instead of having to use the terminal to manage settings we wanted an easy to use and nice looking GUI.

## Requirements

* Ubuntu 18.04, Raspbian Buster or Debian 10
* root user

## Sponsoring

Thanks to [Team Centric Software](http://tcs.de) for sponsoring initial development

## Installation

#### Automatic Install

With our install script all the needed packages for WireGuard and wg-dashboard will be installed. Just follow the given steps.

1. Connect to your server:
	* `ssh <your_vps_user>@<your_vps_ip>`
2. Run the install script
	* `curl https://raw.githubusercontent.com/picassio/wg-dashboard/master/install_script.sh | sudo bash`
3. Go to [http://your_vps_ip:3000](http://your_vps_ip:3000) in your favorite browser
4. Enjoy

## Features

* Dashboard with login system
* Dashboard user management
* Automatic creation of public and private keys for server and peers
* Peer administration
	* Generation of QR Codes
	* VPN configuration download
		* Enable/Disable peers
* WireGuard server management
	* Restart
	* Logs
* WireGuard config management
	* Host / IP
	* Port
	* Network adapter
	* Virtual address 
		* Allowed IP's for VPN clients
* CoreDNS config management
	* DNS Server
	* DNS over TLS
* Clean GUI

## Looking for a cheap VPS?

You are looking for a cheap VPS to run WireGuard on? Check these out:

-   [Hetzner](https://www.hetzner.com/cloud)

#### Get free \$50 credit when you sign up on either of these!

-   [DigitalOcean](https://m.do.co/c/8d5e8ac9b8f1) (affiliate)

## Disclaimer

We are not, in any way, affiliated with WireGuard or their creators.

## Donations

If you would like support this project, please consider donating:

-   Bitcoin: `17WesqNX7ozumrufLWhukDCvwaiywHxny3`
-   Ethereum: `0x5d7836D6d3A10b1b970fb45E8f571A0cA3cE4f57`
-   Bitcoin Cash: `qr3vcp6zngks2mc42vpyakq76wlpngerj5z0e3pq9l`
-   Stellar: `GAA2EKSDAAUNM4GVTIGM7FKJSXCGUKNZKUNURHIUCHJ56M4ITB36F55K`
-   USDPAX: `0x5d7836d6d3a10b1b970fb45e8f571a0ca3ce4f57`
