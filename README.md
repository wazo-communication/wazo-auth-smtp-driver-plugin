# wazo-auth-smtp-driver-plugin

Add SMTP driver for wazo-auth custom email transport

## Installation

```sh
wazo-plugind-cli -c "install git https://github.com/wazo-communication/wazo-auth-smtp-driver-plugin"
```

Installing this plugin will restart `wazo-auth`, impacting API calls.

After installing this plugin, wazo-auth will be able to send emails via custom
plugins. More details about plugin integration at
https://wazo-platform.org/uc-doc/system/wazo-auth/developer/#email-notification.

This plugin is only useful for Wazo servers 25.01.

## Uninstallation

```sh
wazo-plugind-cli -c "uninstall wazocommunication/wazo-auth-smtp-driver-plugin"
```
