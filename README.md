# ChartBalance beta

ChartBalance reads a colour chart through a camera or capture card and tells you which
RGB blacks (lift / pedestal), whites (gain) and mids (gamma) to change so the chart's
greys come out neutral. It also checks exposure. It finds and recognises the chart by
itself: Calibrite / X-Rite ColorChecker (Video, Passport, Classic, Digital SG and more),
Datacolor SpyderCheckr, and DSC Labs ChromaDuMonde and OneShot.

This repository holds the **beta builds** for testers.

## Download

1. Open [Releases](https://github.com/MattVillis/chartbalance-beta/releases) and download
   the newest `ChartBalance-<version>-win64.zip`.
2. Unzip it, open the folder and double-click `ChartBalance.exe` (Windows 10 or 11,
   64-bit). The beta isn't signed: if Windows says "Windows protected your PC", click
   *More info*, then *Run anyway*.
3. `Read me first.txt` in the folder explains the rest, including sample frames to try
   it without a camera.

ChartBalance checks this page for a newer beta once a day and offers it with an *Update*
button at the top of the window.

## Share a capture

Real cameras and capture cards are what ChartBalance is tested and tuned on, so pictures
of a chart from your setup help a lot, especially when something looks wrong.

- **From the next beta:** click *Share this capture* (on the Save step, or in
  *Details → Settings*). It saves a zip with the picture, your camera and settings, the
  capture format and what ChartBalance read, shows it in Explorer and opens the
  [capture form](https://github.com/MattVillis/chartbalance-beta/issues/new?template=capture.yml)
  with most of it filled in. Drag the zip into the form and submit.
- **Until then:** open the [capture form](https://github.com/MattVillis/chartbalance-beta/issues/new?template=capture.yml),
  fill it in and attach a still of the chart as it came from the camera or capture card
  (a PNG, not a screenshot of the app).

You need a free GitHub account, and everything in the form is public. No account, or a
file over 25 MB? Email it to **matt@frequency.ee** instead.

## Feedback

Email **matt@frequency.ee** with what you did, what you expected and what happened, which
chart and camera you used, a screenshot, and the report from *Details → Settings → Save
report*. If something went wrong, attach `%APPDATA%\ChartBalance\error.log`.
