# Hassio Add-ons by rogierg: checkmk

ATTENTION: this add-on container should be considered unstable.

## About

[Checkmk](https://checkmk.com/) is a leading tool for Infrastructure and Application Monitoring. Simple configuration, scalable, flexible. Open Source and Enterprise.

This addon is based on this [docker image](https://hub.docker.com/r/rogierg/rpi-checkmk).

## Installation

The installation of this add-on is pretty straightforward and not different in
comparison to installing any other Hass.io add-on.

1. [Add my Hass.io add-ons repository][repository] to your Hass.io instance.
1. Install this add-on.
1. Click the `Save` button to store your configuration.
1. Start the add-on.
1. Check the logs of the add-on to see if everything went well.
1. Carefully configure the add-on to your preferences, see the official documentation for for that.


## Configuration

The login details can be found in the log file. Webui can be found at `<your-ip>:5000/mon/check_mk/login.py`.

[repository]: https://github.com/rogierg/hassio-addons
