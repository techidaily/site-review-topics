---
title: Identify malfunctioning hardware drivers with Windows Device Manager in Windows 7
date: 2024-04-29T22:56:21.959Z
tags: 
  - driver
  - device driver
categories: 
  - apps
  - windows
description: This article describes Identify malfunctioning hardware drivers with Windows Device Manager in Windows 7. Device Manager is a control panel applet in Microsoft Windows operating systems. It allows users to view and control the hardware attached to the computer. When a piece of hardware is not working, the offending hardware is highlighted for the user to deal with. The list of hardware can be sorted by various criteria. Device Manager was introduced with Windows 95 and later added to Windows 2000. In NT-based versions, it is included as a Microsoft Management Console snap-in.
keywords: identify missing drivers in Windows 7,identify missing drivers in Windows 11/10/7,install drivers,update drivers,identify missing drivers in Windows 10,identify malfunctioning drivers in Windows 11/10/7
---


## How to identify missing or malfunctioning drivers with Windows Device Manager

To see which of your devices have a missing or malfunctioning driver:

- **Step1**: On your keyboard, press the `Windows logo key`  and `R` at the same time to invoke the Run box.
- **Step2**: Type `devmgmt.msc` and click `OK`.
  
![devmgmt.msc](https://tools.techidaily.com/images/apps/drivereasy/device-manager/1.jpg) 
> (There are other ways to open Device Manager; it changes depending on your version of Windows. But the above method works for all versions of Windows, including Windows 11, 10 and 7.)
>

- **Step3**: Expand a category (e.g. Display Adapters) to see the devices in that category. If you see a yellow triangle or question mark next to a device, Windows has detected that it has a missing or malfunctioning driver.

![Device Manager](https://tools.techidaily.com/images/apps/drivereasy/device-manager/2.jpg)

- **Step4**: If you see this yellow mark, you can try to `update` or `reinstall` the driver.




## What are drivers?

Drivers are like interpreters between Windows and your devices. For example, when Windows needs to display something on your monitor, it sends a command to your graphics card, and your graphics card then displays what Windows wants on your monitor.

But Windows and your graphics card don’t actually speak the same language. To understand each other, they need a translator. That translator is called a driver. It takes the Windows command and translates it into something your graphics card can understand. Your graphics card can then do as it’s told, and display the right thing on your monitor.

Similarly, if your graphics card needs to send some sort of response back to Windows, the driver translates the response into something Windows can understand.

In this example, what we’re talking about is a video driver, but your computer has many other drivers on it too – one for each device. Your speakers, your printer, your mouse, your USB hard drives, your network card, your keyboard and so on – they each have an associated driver.

And without all these drivers, none of your devices will work.

![What are drivers?](https://tools.techidaily.com/images/apps/drivereasy/pages/why_2.jpg)

## All our drivers are certified

We use only genuine drivers, straight from your hardware manufacturer. And we employ a strict testing process to ensure they’re safe, stable, robust, up-to-date, and compatible with Windows and all the most popular combinations of hardware and software.

### Microsoft WHQL Testing

Most hardware manufacturers put their drivers through Microsoft’s rigorous Windows Hardware Quality Labs (WHQL) testing process. If they pass, they’re officially certified stable and compatible with Windows.

If your manufacturer has a ‘Certified for Windows’ driver, that’s the one we’ll use. For Windows 10 and 11, Driver Easy installs only drivers that are ‘Certified for Windows’ through the Windows Hardware Quality Labs (WHQL) program. For Windows 7, 8 and Vista, Driver Easy installs WHQL drivers by default, if they’re available (which they are for 95.69% of drivers for those versions of Windows), but also gives users the option to install non-WHQL drivers.

But we don’t stop there. We also perform our own tests to ensure the stability of our drivers…

### Certified by Driver Easy

We employ a strict testing regime to ensure our drivers are safe, secure and stable.

This is critical because not all manufacturers get their drivers certified by Microsoft – particularly for older hardware. (It’s a very rigorous and time-consuming process, and for manufacturers with a lot of devices and drivers, it can become quite expensive.)

## We test on all the most popular combinations of hardware & software

Our tests are a lot more hands-on and practical than Microsoft’s tests. Because drivers behave differently on different computers, different versions of Windows, and even in the presence of different software applications, the only way to really tell if a driver will be stable, compatible and safe for everyone is to physically test it on all the popular hardware / operating system / software combinations. So that’s what we do:

- We test on hundreds of PCs – Our testing facility is strategically located in Shenzhen, China, one of the country’s biggest IT hubs. We specifically selected this estate because we’re surrounded by hundreds of PC distributors, all within walking distance. This means we have unfettered access to an almost limitless supply of hardware, and can physically test our drivers on all the most popular computers – including the latest new models available on the market, as well as second-hand computers that still have a wide user base. 
- We test with physical devices attached – For external device drivers (e.g. for printers, external hard drives, mice, keyboards), we physically install the external device to test the driver.
- We test on all current versions of Windows – On each test PC, we install and test thoroughly on Windows 11 32-bit, Windows 11 64-bit, Windows 10 32 bit, Windows 10 64-bit, Windows 7 32-bit and Windows 7 64-bit.
- We test with popular programs installed – On each installation of Windows, we also install a variety of popular software programs before testing the driver (e.g. various versions of Microsoft Office, antivirus products and video players).

## Here’s our full testing process

We subject all new drivers to a battery of tests.

### Step 1. Filter out faulty drivers

First, we locate and download any new drivers from nearly 100 manufacturer websites, then scan them all with two proprietary tools that filter out any that:

- are incorrectly formatted;
- are missing files;
- are likely to be flagged by antivirus programs; or
- have failed our previous tests.
Then we add all drivers that pass these filters to our development-only version of Driver Easy.

### Step 2. Test on all modern versions of Windows

We then scan a small selection of computers with our development-only Driver Easy. These computers have typical devices attached, like a mouse, keyboard, monitor and printer. On each computer, we test all modern versions of Windows (Windows 11 32-bit, Windows 11 64-bit, Windows 10 32 bit, Windows 10 64-bit, Windows 7 32-bit and Windows 7 64-bit):

- **01.** We install each driver that Driver Easy recommends, one at a time.

- **02.** After each driver installation, we check that the computer functions normally and all devices work properly. E.g. If it’s a network card driver, we test the internet connection, if it’s a video card driver, we test the screen resolution, if it’s a keyboard driver, we test that the keyboard is functioning properly, and so on.

- **03.** We then check Windows’ Device Manager to ensure no device drivers are flagged as problematic.

- **04.** We then restart the computer to ensure that the driver installation didn’t cause any issues with Windows (e.g. no blue screen of death on startup, no error messages, no unexpected behavior).

- **05.** If all is working as expected, we return to step 1, and install and test the next driver.

- **06.** If there are issues, we check the driver install log to see if any errors were detected during installation.

- **07.** If the log is inconclusive, we do further testing to determine if it was the driver that caused the issue. Usually we test an alternative driver to see if it causes the same issue. If it doesn’t, then it’s likely the first driver is the culprit. If the same issue occurs with the alternative driver too, we test to see if the computer itself is the issue. Often this involves performing a system restore on the test PC.

- **08.** If we can prove that the driver was the cause of the computer or device issue, we remove it from Driver Easy, then return to step 1, and install and test the next driver.

Any drivers that make it through our first two test phases are then added to the live Driver Easy database.

### Step 3. Test on many popular computers

We then use Driver Easy to scan dozens of the most popular computer setups (PC, operating system, video card, sound card, network card, printer, default software, etc.):

- 01. We install each driver that Driver Easy recommends, one at a time.

- 02. After each driver installation, we check that the computer functions normally and all devices work properly. E.g. If it’s a network card driver, we test the internet connection, if it’s a video card driver, we test the screen resolution, if it’s a keyboard driver, we test that the keyboard is functioning properly, and so on.

- 03. We then check Windows’ Device Manager to ensure no device drivers are flagged as problematic.

- 04. We then restart the computer to ensure that the driver installation didn’t cause any issues with Windows (e.g. no blue screen of death on startup, no error messages, no unexpected behavior).

- 05. If all is working as expected, we return to step 1, and install and test the next driver.

- 06. If there are issues, we check the driver install log to see if any errors were detected during installation.

- 07. If the log is inconclusive, we do further testing to determine if it was the driver that caused the issue. Usually we test an alternative driver to see if it causes the same issue. If it doesn’t, then it’s likely the first driver is the culprit. If the same issue occurs with the alternative driver too, we test to see if the computer itself is the issue. Often this involves performing a system restore on the test PC.

- 08. If we can prove that the driver was the cause of the computer or device issue, we remove it from Driver Easy, then return to step 1, and install and test the next driver.

Over the course of a year, we test on hundreds of different computers in this way.

If a driver fails our tests…
If we establish that a manufacturer’s driver causes issues on any combination of hardware, operating system and software, we find an alternative version of the driver for that particular combination.

For example, if an audio driver supplied by Dell for a certain laptop causes issues on Windows 10, we’d source a different version of it. Typically from the audio card’s chipset manufacturer (e.g. Realtek). They’d usually have the most up-to-date drivers available because they continue updating their drivers almost indefinitely, whereas Dell would typically stop updating the laptop’s drivers as soon as it’s superseded by a newer model.

Once we’ve located an alternative driver, we start over at step 1 of our testing process with it.

## Try Driver Easy for free

If you want the certainty of knowing your device drivers are always up to date (and not just sometimes up to date, which is all you get from Windows Device Manager), and you don’t have the time, patience or computer skills to continually update them manually, give the free version of [Driver Easy](https://tools.techidaily.com/drivereasy/download/) a try.

[Download Free Version](https://tools.techidaily.com/drivereasy/download/)

The free version will identify all your outdated drivers, and allow you to download them all. But only one at a time and, once they’re downloaded, you have to manually install them using the standard Windows process. (To automatically update all your drivers with 1 click, you’ll need [the Pro version of Driver Easy](https://tools.techidaily.com/drivereasy/download/). Don’t worry, it comes with a 30-day, no-questions-asked, money back satisfaction guarantee.)




## Why you can’t rely on Windows to keep your drivers up-to-date

Windows comes with an inbuilt tool, called ‘Windows Update’, that’s supposed to automatically keep your drivers up to date. Unfortunately, it doesn’t work very well.

There are two reasons why…

- Device manufacturers often take a long time to get their drivers into a Windows Update – It’s a time-consuming and difficult process. Sometimes they just miss the deadline and have to wait ‘til the next Windows Update, and sometimes they just give up altogether. In fact, for older devices, this is the norm.

- Windows Update ignores driver updates it considers ‘optional’ – It categorizes driver updates as either ‘critical’, ‘automatic’ or ‘optional’, and it doesn’t usually concern itself with the ‘optional’ ones – even when they’re actually important. You can install them manually by going to the ‘Optional updates’ screen but, even then, as described above, you’re unlikely to get all the latest drivers.

## What happens if a driver is missing or outdated?

Every now and then, Microsoft will change the commands Windows sends to one of your devices (e.g. your network card). When this happens, the manufacturer of that device need to change the device driver too. They need to teach it the new Windows commands. Otherwise the drivers won’t be able to translate those commands for your devices, and your devices won’t work properly.

The same thing needs to happen when your device manufacturer changes the way your device talks, or the things it can do. They need to change the driver too. Otherwise Windows won’t be able to talk to the device, or take advantage of its new functionality, and your device won’t work properly.

Now when we say “your device won’t work properly”, sometimes this means simply that you miss out on new functionality or minor bug fixes. But it’s often a lot more serious than that. Your computer may even hang, crash or stop working completely. Remember, there’s a driver that controls your hard drive, for instance. If Windows can’t talk to your hard drive, it can’t access any of the data on your drive. Similarly, if Windows can’t talk to your network card, you won’t be able to access the internet, and if it can’t talk to your graphics card, you won’t be able to see anything on your monitor. These are just a few of the more serious issues outdated drivers can cause.

![What happens if a driver is missing or outdated?](https://tools.techidaily.com/images/apps/drivereasy/pages/why_3.jpg)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<ins class="adsbygoogle"
    style="display:block"
    data-ad-format="autorelaxed"
    data-ad-client="ca-pub-7571918770474297"
    data-ad-slot="1223367746"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-15-pro-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 15 Pro to other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-redmi-k70-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Redmi K70.</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-pictures-from-poco-x6-by-fonelab-android-recover-pictures/"><u>Possible solutions to restore deleted pictures from Poco X6.</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-15-to-other-iphone-12-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 15 to other iPhone 12 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-mkv-video-on-xiaomi-redmi-note-12r-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Issues playing MKV video on Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-7-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 7 To Other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/online-signatures-for-dotx-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>Online signatures for .dotx file</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-12-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 12 without iTunes? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-mkv-video-on-redmi-note-12-4g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Issues playing MKV video on Redmi Note 12 4G</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-honor-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Honor</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Fixing Foneazy MockGo Not Working On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-vivo-v30-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after Vivo V30 has been deleted.</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-oneplus-open-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on OnePlus Open</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-poco-c55-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Poco C55 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-samsung-galaxy-a05s-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Samsung Galaxy A05s</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-15-to-android-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 15 To Android? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 11 to other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Motorola G54 5G? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/insert-signature-in-uot-file-by-ldigisigner-sign-a-word-sign-a-word/"><u>Insert signature in .uot file</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-mov-videos-on-14-pro-by-aiseesoft-video-converter-play-mov-on-android/"><u>Issues playing MOV videos on 14 Pro</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-separate-audio-from-video-in-davinci-resolve-step-by-step/"><u>New In 2024, Separate Audio From Video in DaVinci Resolve Step by Step</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-10-best-romance-anime-movies-you-need-to-watch/"><u>New 10 Best Romance Anime Movies You Need to Watch</u></a></li>
<li><a href="https://animation-videos.techidaily.com/best-15-instant-classics-animated-cartoon-movies-for-2024/"><u>Best 15 Instant Classics Animated Cartoon Movies for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-oppo-reno-11-5g-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Oppo Reno 11 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-vivo-t2x-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Xiaomi Redmi Note 12 4G? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-itel-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Itel Devices</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-nokia-c210-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Nokia C210 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-poco-x6-pro-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Poco X6 Pro Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
</ul></div>

