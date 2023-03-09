# Installing SideStore

### Requirements:
to install sidestore, you will need the following:

- a computer (windows, macos, or linux will work fine)
- your phone (obviously)
- a cable to connect your phone to your computer
- common sense
- just a little bit of time

this isn't going to be hard at all.

### Tutorial:
1. you're going to need to get on your computer and download [JitterbugPair](https://github.com/osy/Jitterbug/releases/latest). download the zip file that works on your device.
2. unzip the file you downloaded and extract the binary to somewhere accessible.
3. if you're on windows, open the command prompt. for macos and linux users, open a terminal.
4. change directories into the location where you extracted the binary.
5. connect your phone to your computer, while it is on the homescreen.
6. run the binary. on windows, just run `jitterbugpair.exe` and on macos and linux, run `./jitterbugpair` (you might have to run `chmod +x jitterbugpair` before executing).
7. you should now be prompted to trust the computer, click trust and enter your passcode if prompted.
8. run jitterbugpair again.
9. you should now have a file with the file extension `.mobiledevicepairing`. keep the file name, which should be your udid, but change the file extension to `.plist`.
10. send the `.plist` file to your phone. you can use a discord channel, saved messages on telegram, or any other way to transfer the file. make sure you don't save the file to your iCloud Drive.
11. download [SideStore.ipa](https://github.com/SideStore/SideStore/releases/latest/download/SideStore.ipa) and sideload it using AltStore or Sideloadly. for linux users, you can use [AltServer-Linux](https://github.com/NyaMisty/AltServer-Linux). just make sure to use a solution that uses your apple developer account.
12. open sidestore once it's done sideloading and select the `.plist` file you should have on your phone.
13. if you don't have the wireguard app, install it [from the app store](https://apps.apple.com/us/app/wireguard/id1441195209).
14. open wireguard and add the following [configuration file](https://github.com/SideStore/SideStore/releases/download/0.1.1/SideStore.conf). now connect to it.
15. now open settings and look for sidestore in the apps section. now just select an anisette server to use.

**NOTE**: public anisette servers will usually lock your apple id. however, [you can create your own for free](https://wiki.sidestore.io/guides/custom-anisette.html#deploy-on-render).

16. pretty much done! while sidestore's wireguard profile is on, you can refresh and install apps without a computer. if you don't use any vpns, you can leave the profile always on and sidestore will automatically refresh the apps for you. if you don't want to leave it always on, you can create a reminder that reminds you to turn on the vpn profile and renew the app every 6 days.
17. (optional) if you were using altstore before, you can now remove it as you will no longer need it.
