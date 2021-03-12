This folder is the one you want if you just want to load orpheus up into the program of your choice.

There are a bunch of programs that these files will work in. Here's a list of a few:

- VTube Studio
- Live2D Cubism Viewer
- Animaze (aka FaceRig)

Personally I use VTube Studio, so that's the only setup instructions I can write in here. Other software tutorials should be available if you just google "Live2D import into Animaze" (with the name of the software you want to use)

## Using in VTube Studio

_This is a simplified version of the [official docs](https://raw.githubusercontent.com/DenchiSoft/denchisoft.github.io/master/docs/VTube_Studio_Documentation.pdf). If something here is wrong or confusing, you can find the truth there._

First install VTube Studio. You'll require an iPhone where you should [install the app in the app store](https://apps.apple.com/us/app/vtube-studio/id1511435444) and a computer were you can install the Mac or Windows version of VTube Studio ([steam link](https://store.steampowered.com/app/1325860/VTube_Studio/) [itch.io link](https://denchi.itch.io/vtube-studio)) (Windows is a little more feature complete).

Now you can load up the model by copying this folder which directly contains:
- Orpheus.moc3
- Orpheus.model3.json
- Orpheus.cd3.json
- a few other files & folders...

into the VTube Studio's data folder. For me on a Mac, this is at `/Applications/VTubeStudio.app/Contents/Resources/Data/StreamingAssets/Live2DModels`, but will be different on Windows and other Macs.

Once it's copied over, go open VTube Studio & you should see an option in the model picker for Orpheus.

![](https://cloud-pwis3trpr-hack-club-bot.vercel.app/1screen_shot_2021-03-12_at_5.44.13_pm.png)

For first time configuration, you'll get a popup asking if you want to configure for iPhone or Android. For this tutorial I'll assume you're using iPhone (which is more feature-complete then Android).

Now go into the model settings and switch the eye inputs (`EyeOpenRight` should input to "Eye Open Left" & vice-versa). I'm not sure why we have to do this, it's probably a bug in the way I'm exporting my model. The photo below shows a correct mapping of inputs:

![](https://cloud-8ufk9an1f-hack-club-bot.vercel.app/0screen_shot_2021-03-12_at_6.00.22_pm.png)

Now you can run the server from your computer & connect your phone for face tracking!