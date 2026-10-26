# Klok

Klok is a flipping clock I actually use. I wanted one place for the time, a timer, a pomodoro, and a calendar I can glance at, so I built it that way.

It is a product of Mark8 Production.

Home: https://klok.mark8production.net

## What it looks like now

This version is a station departure board. The clock fills the screen with huge split-flap tiles that flip like a real board, with hinge pins and deep shadows. It feels mechanical, not like a normal app clock.

## What it does

- A big split-flap clock that flips every second, with a 12 hour and 24 hour switch
- World clocks for Kathmandu, Chicago, and London, shown as board rows with their codes, KTM, CHI, and LON
- A timer with presets, pause, resume, reset, and a beep when it finishes
- A pomodoro with Focus, Short break, and Long break, where you can change the lengths and it remembers them
- A date-only calendar inside the Clock tab: a tear-off sheet and a month grid you can browse, tap a date, and tear to the next day
- Both black and white themes, with a toggle that remembers your choice. White is white paper with black ink, Black is true black with white ink

Everything is black and white, on purpose. No colour noise, just the clock and the work.

## One honest note about the calendar

In this public version, there is no to-do list and nothing is saved. There is no account and nothing is saved on a server, so the calendar is for looking at the date, not for keeping tasks. That is by design for this version. My private version is separate and does save entries, but this public one is meant to be simple and light.

## Run it yourself

There is no build step and nothing to install. This is a single static page.

1. Download or clone this repo
2. Open `index.html` in a browser

That is it. It works on phone, tablet, and desktop.

## Files

- `index.html` - the whole app, in one file
- `README.md` - this file

## Built with

Plain HTML, CSS, and JavaScript. No framework, no backend, no database.

If you use it and something feels off, that feedback helps more than a star. I built Klok to be used every day, not just looked at once.
