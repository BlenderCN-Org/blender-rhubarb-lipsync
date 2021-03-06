# Blender Rhubarb Lip Sync

Blender Rhubarb Lipsync is an addon for [Blender](http://blender.org) integrating [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) to automatically generate mouth-shape keyframes from a pose library.

Rhubarb Lip Sync is a command-line tool that automatically creates mouth animation from voice recordings. You can use it for characters in computer games, in animated cartoons, or in any other project that requires animating mouths based on existing recordings.

## Example output

[![Example video](http://img.youtube.com/vi/azrpByrvw-o/0.jpg)](http://www.youtube.com/watch?v=azrpByrvw-o)

http://www.youtube.com/watch?v=azrpByrvw-o

and here's a tutorial video from Studio YogYog

[![Tutorial video](http://img.youtube.com/vi/xfI94VIX6BA/0.jpg)](https://youtu.be/xfI94VIX6BA)

https://youtu.be/xfI94VIX6BA

## Usage

Download a release from https://github.com/scaredyfish/blender-rhubarb-lipsync/releases

_Use version 1.0.5 for Blender 2.79, version 2.0 onwards supports only Blender 2.80._

First, set the path to the Rhubarb Lipsync executable in user preferences (download from [https://github.com/DanielSWolf/rhubarb-lip-sync](https://github.com/DanielSWolf/rhubarb-lip-sync))

You can also set the recognizer here. PocketSphinx is recommended for English language, phonetic may give better results for other languages.

![Preferences](img/prefs.PNG)

Create a [pose library](https://docs.blender.org/manual/en/dev/rigging/armatures/properties/pose_library.html) with the mouth shapes described in the Rhubarb Lip Sync documentation. You can name your poses whatever you like.

![Pose library](img/poselib.PNG)

Match your poses with the Rhubarb Lip Sync names.
Select your sound file, and dialog file (optional), and the start frame where your sound begins.

![Options panel](img/panel.PNG)

In pose mode, select the bones you want to keyframe, then click the Rhubarb Lip Sync button and wait for the process to complete. There is no progress indicator yet, but your keyframes will appear when the process is complete.

## Troubleshooting

In the event of problems, you can use the system console (Window->Toggle System Console on Windows, or start Blender from a command line on Mac/Linux) to get more info on progress and error messages.
