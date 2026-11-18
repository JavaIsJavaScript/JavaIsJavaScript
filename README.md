### Hi, I'm David

Software engineer from the Netherlands. Most of my time now goes into **Allsono**, an app I build on my own, for Android, iOS, Mac, Windows and Linux.

<a href="https://allsono.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/allsono-banner-dark.png">
    <img src="assets/allsono-banner.png" alt="Allsono: one song, every room" width="100%">
  </picture>
</a>

## Allsono

Allsono turns the phones and computers you already own into speakers that play in sync, in every room. One device is the source and the others play along, over your own Wi-Fi. No new speakers, the sound never leaves your home network, and an account is optional.

<p>
  <a href="https://play.google.com/store/apps/details?id=com.allsono.android"><img src="assets/google-play.png" alt="Get it on Google Play" height="48"></a>
  &nbsp;
  <a href="https://apps.microsoft.com/detail/9NKF53BX17G7"><img src="assets/get-it-from-microsoft.png" alt="Download from the Microsoft Store" height="48"></a>
  &nbsp;
  <a href="https://allsono.com/download"><img src="assets/download-mac.png" alt="Download for Mac" height="48"></a>
  &nbsp;
  <a href="https://allsono.com/download/linux"><img src="assets/download-linux.png" alt="Download for Linux" height="48"></a>
</p>

<table>
  <tr>
    <td><picture><source media="(prefers-color-scheme: dark)" srcset="assets/allsono-1-dark.png"><img src="assets/allsono-1.png" alt="Turn your phones into speakers in every room" width="260"></picture></td>
    <td><picture><source media="(prefers-color-scheme: dark)" srcset="assets/allsono-2-dark.png"><img src="assets/allsono-2.png" alt="Set every speaker's volume from your phone" width="260"></picture></td>
    <td><picture><source media="(prefers-color-scheme: dark)" srcset="assets/allsono-3-dark.png"><img src="assets/allsono-3.png" alt="Every room plays in sync" width="260"></picture></td>
  </tr>
</table>

**What's inside**

- **Android app** in Kotlin and Jetpack Compose. It captures the sound of other apps and sends it to the speakers.
- **Mac and iOS apps** in Swift and SwiftUI, sharing one Swift core. On the Mac, Core Audio captures the system sound.
- **Windows app** in C# and WPF on .NET 10, from the Microsoft Store. It captures the sound of other apps with WASAPI process loopback, no driver needed.
- **Linux app** in Java and JavaFX, as a .deb with signed self-updates. It captures the system sound through its own PulseAudio/PipeWire sink.
- **My own sync protocol** over the local network. A shared clock keeps every device within a few milliseconds, with uncompressed 16-bit 48 kHz stereo.
- **allsono.com** with Spring Boot (Java) and Vue: accounts, settings sync across devices, and updates for Mac and Linux.
- English, Dutch, German and French. CI on my own runners, deploys on every push.

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose">
  <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift">
  <img src="https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/JavaFX-007396?style=flat-square&logo=openjdk&logoColor=white" alt="JavaFX">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue.js">
</p>

## Find me

[allsono.com](https://allsono.com) · [rerimassie.nl](https://www.rerimassie.nl)
