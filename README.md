PS3 Visual Retailkit

A lightweight visual overlay for PS3 on CFW and HEN, designed to give your console a clean devkit-style HUD.
Originally starting in v0.02 as a simple firmware label, it evolved into a functional on-screen info overlay by v0.5b, and has now been refined in v0.7b to include multiple dynamic elements.

Features (v0.7b)

Rendered using the XMB-style msgtext system:

SYS: 4.92.1.098.59 DEV ★
HEN: %HENVERSION%
IP: %IP%


Smooth rainbow color-cycling for all text

Bottom-right corner positioning with offsets

Optimized for 1080p / 1080i

Fully compatible with CFW and HEN

Displays dynamic system info: system version, HEN version, and IP address

Usage

Copy the overlay XML to your PS3:

/dev_hdd0/custom_retailkit.xml


Load it with a plugin that supports custom overlays, e.g., webMAN MOD.

The overlay will appear on the XMB and in homebrew that supports on-screen text rendering.

This HUD is cosmetic only — it does not modify firmware or flash.

Version History

v0.02 — initial firmware version label
v0.5b — added IP, FPS, IDPS, improved layout, added 1080p/1080i support
v0.6b — removed IP/FPS/IDPS, simplified layout
v0.7b — added dynamic elements via msgtext (SYS, HEN, IP), refined offsets, smooth rainbow cycling

Purpose

The goal is simple:
Provide a subtle devkit-inspired overlay for retail PS3 systems without touching system files.
Safe for both CFW and HEN consoles.

Credits

a-xpk — GitHub
rj3y — Discord
fortumart.com — Snapchat

Support the Project
<a href="https://ko-fi.com/a_xpk"> <img src="https://storage.ko-fi.com/cdn/kofi3.png" width="200" alt="Support on Ko-fi"> </a>
