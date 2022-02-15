---
description: This tells the remote publishers to send keyframes at a specified rate
---

# \&keyframerate

## Aliases

* `&keyframeinterval`
* `&keyframe`
* `&kfi`

## Options

| Value           | Description    |
| --------------- | -------------- |
| (integer value) | interval in ms |

## Details

Could be useful if packet loss is causing a lot frame corruption.

If you make it less than 1000ms, you will face a pretty steep drop in video quality.

It may not work at all if set too low; under 500ms didn't work at all in my testing.