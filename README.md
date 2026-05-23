<div align="center">
  
# 👋 Hey, I'm Shanu Kumawat

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=600&lines=Systems+Software+Engineer;Hacking+the+Linux+Desktop;Building+Dart+SDK+Tools;Learning+Rust+%26+DSA)](https://git.io/typing-svg)

**Building tools close to the metal.**

<a href="https://linkedin.com/in/shanukumawat"><img src="https://img.shields.io/badge/LinkedIn-d5d5d5?style=for-the-badge&logo=linkedin&logoColor=0A0209" alt="LinkedIn profile" /></a>
<a href="https://x.com/shanu_builds"><img src="https://img.shields.io/badge/Twitter-d5d5d5?style=for-the-badge&logo=x&logoColor=0A0209" alt="Twitter profile" /></a>
<a href="mailto:hello@shanukumawat.com"><img src="https://img.shields.io/badge/Email-d5d5d5?style=for-the-badge&logo=gmail&logoColor=0A0209" alt="Email me" /></a>

</div>

---

## 🚀 About Me

Hey! 👋 I'm Shanu.

I'm currently a B.Tech student at MNNIT Allahabad. My actual major is Computational Mechanics, but to be honest, I spend almost all my time writing code and hanging out in open-source communities.

Right now, my free time mostly goes into hacking on the Linux desktop and poking at language compilers. I created and currently maintain the **[Quickshell Overview](https://github.com/Shanu-Kumawat/quickshell-overview)** module for Hyprland (which just hit 375+ stars! ⭐), and I recently started contributing patches to the core Google Dart SDK.

I'm definitely most interested in lower-level programming. These days, I'm mostly writing C++, Dart, and Rust. Whether it's dissecting Wayland protocols, patching Virtual Machines, or messing with native memory, I just really enjoy figuring out how things actually work under the hood.

```yaml
current_focus:
  learning: "Data Structures & Algorithms, Rust"
  building: "RentKhata (Offline-first property management app for Indian landlords)"
  exploring: "Dart VM internals, OS memory APIs, and Debug Adapters"
```

---

## 🏆 Work I'm Proud Of

Getting code into massive enterprise compilers is intimidating, but it's where I learn the most. Here are some of my recent open-source contributions to the core **Google Dart SDK**:

*   **[Merged CL: Check @Native on extension members](https://dart-review.googlesource.com/c/sdk/+/482160)** - Aligned analyzer diagnostics with CFE behavior for extension-like members while preserving pointer-receiver restrictions.
*   **[Issue #62716: Analyzer crashes on @Native in extension method](https://github.com/dart-lang/sdk/issues/62716)** - Discovered and documented an analyzer crash deep in `ExtensionElementImpl` while working on FFI bindings.

---

## 🐛 The Weirdest Bug I've Fought Recently

I think you can tell a lot about an engineer by the bugs they fight. Recently, while patching the Dart VM for my Native Memory Inspector, my memory reads kept silently failing on Windows despite working perfectly on Linux. 

After digging deep into the C++ runtime source, I discovered it was an **LLP64 truncation bug**. On Windows, an `unsigned long` is only 32 bits, meaning my 64-bit memory addresses were being silently truncated when passed through the RPC parser. Switching it to `UInt64Parameter` fixed the crash entirely. It was a brutal debugging session, but it perfectly sums up why I love low-level systems programming.

---

## 🎯 Featured Work

<table>
<tr>
<td width="50%">

### 🏢 [RentKhata](https://github.com/Shanu-Kumawat/RentKhata)
**Offline-First Property Management**

An offline-first app designed specifically for Indian landlords. Helps track rent, calculates electricity bills from meter readings, manages tenants, and automatically generates and sends PDF receipts over WhatsApp. Works 100% without internet.

**Tech:** Flutter • Local Storage • PDF Generation
</td>
<td width="50%">

### 🔍 [Native Memory Inspector](https://github.com/Shanu-Kumawat/native_memory_inspector)
**Dart VM Memory Debugger**

A standalone Flutter desktop app and Dart VM patchset that uses OS-level APIs (`process_vm_readv` / `ReadProcessMemory`) to safely read, decode, and visualize raw C-struct memory without crashing the target isolate.

**Tech:** C++ • Dart VM • Flutter Desktop • FFI
</td>
</tr>
<tr>
<td width="50%">

### 🪟 [Quickshell Overview ⭐ 375+](https://github.com/Shanu-Kumawat/quickshell-overview)
**Hyprland Workspace Manager**

A highly popular standalone workspace overview module for Hyprland. Features live application window previews, drag-and-drop workspace support, and modular system keybind integrations.

**Tech:** Quickshell • Hyprland Protocol • QML
</td>
<td width="50%">

### 🔦 [Beacon](https://github.com/Shanu-Kumawat/Beacon)
**AR Navigation for Visually Impaired**

AR-powered navigation app combining real-time object detection with voice guidance. Optimized computer vision models for mobile performance while maintaining safety-critical accuracy.

**Tech:** Flutter • Firebase • AR Kit
</td>
</tr>
</table>

---

## 🛠️ Tech Stack & GitHub Stats

<details>
<summary><b>Click to expand</b></summary>
<br>

### Languages
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Frameworks & Systems
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### 📊 GitHub Stats

<table>
  <tr>
    <td rowspan="3" width="55%">
      <img src="https://github-readme-stats-git-master-rickstaa.vercel.app/api/top-langs/?username=Shanu-Kumawat&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&langs_count=10" width="100%" />
    </td>
    <td width="45%">
      <img src="https://github-readme-stats-git-master-rickstaa.vercel.app/api?username=Shanu-Kumawat&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" width="100%"/>
    </td>
  </tr>
  <tr>
    <td>
      <img src="https://streak-stats.demolab.com?user=Shanu-Kumawat&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" width="100%"/>
    </td>
  </tr>
</table>

</details>

---

## 🤝 Let's Connect

I'm always down to chat. If you ever want to connect, here are a few things you can ask me about to get the conversation started:

*   How to get started with contributing to massive language compilers (like the Dart SDK).
*   The absolute nightmare (and joy) of configuring Wayland compositors and Linux rices.
*   Why you should definitely *not* use `unsigned long` for memory addresses on Windows.
*   Anything related to low-level C++ or Rust.

Whether you have a tough debugging problem, want to collaborate, or just want to say hi, feel free to shoot me an email!

<div align="center">

<a href="https://linkedin.com/in/shanukumawat"><img src="https://img.shields.io/badge/LinkedIn-d5d5d5?style=for-the-badge&logo=linkedin&logoColor=0A0209" alt="LinkedIn profile" /></a>
<a href="https://x.com/shanu_builds"><img src="https://img.shields.io/badge/Twitter-d5d5d5?style=for-the-badge&logo=x&logoColor=0A0209" alt="Twitter profile" /></a>
<a href="mailto:hello@shanukumawat.com"><img src="https://img.shields.io/badge/Email-d5d5d5?style=for-the-badge&logo=gmail&logoColor=0A0209" alt="Email me" /></a>

</div>
