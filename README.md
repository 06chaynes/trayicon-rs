# TrayIcon

Currently I target Windows tray icon implementation, with popup, click, double click. Goal is to provide a channel for events and ability to plug in [winit](https://github.com/rust-windowing/winit) event loop easily.

## Alternatives

Most mature alternative is qdot's [systray-rs](https://github.com/qdot/systray-rs). Unfortunately I got frustrated with the API in it and decided to rewrite my own.

This however largely does not use the code in it, instead I loaned my old C/C++ code as a template.