# Home Assistant with myChevy and Selenium

This is a fork of https://github.com/home-assistant/home-assistant

See official documentation from there.  Inspired by https://github.com/taskinen/home-assistant

## New features

Added [Selenium](https://www.seleniumhq.org/) with the Chrome driver, Chrome Browser and the myChevy python module on top of the Home Assistant docker instance in order to get charge stats on my Gen 1 Chevy Volt

## Why?

In order to monitor the charge status of my Chevy Volt via the [myChevy]() component, I needed my Home Assistant instance to include the Selenium software package.  While this is relatively easy to install on bare-metal configurations, making it persistent in my Docker configuration requires either a janky and unreliable installation into the config path or Doing It Right(tm).
