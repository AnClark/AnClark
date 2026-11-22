# Welcome to AnClark Liu's GitHub repo!

This is AnClark Liu, a part-time software developer & musician. I always love Free & Open Source and contributing to FOSS projects.

## Skills

- Good master of audio plugin developments ([DPF](https://github.com/DISTRHO/DPF)-based)

- Programming languages:
  - Mastered: C, C++, Python, JavaScript (ES5), HTML/CSS
  - Learning: Lua
- Researches:
  - Audio plugin developments & implementations
  - TWRP Recovery porting (until 2019)
  - OpenWRT build

## Portfolio

### Audio Plugins

| Project                                                      | Introduction                                                 | Note |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
|[Comprez](https://github.com/AnClark/Comprez)|A light-weight compressor based on Heavylib, with a vintage-style fuzz effect||
|[Minaton-XT](https://github.com/AnClark/Minaton-XT)          | DPF port of Minaton, an analog-modeled synthesizer by ThunderOx |      |
|[CetoneSynthLight](https://github.com/AnClark/CetoneSynthLight)|DPF port of CetoneSynthLight, an old-school synthesizer by Neotec Software. I implemented **polyphony** and preset manager. |     |
|[CetoneSynth](https://github.com/AnClark/CetoneSynth)             | DPF port of CetoneSynth, the deluxe version of CetoneSynthLight. I implemented **polyphony** and preset manager. |       |
|[Cetone033](https://github.com/AnClark/Cetone033)             | DPF port of Cetone033, a chiptune-style bassline & lead synthesizer by Neotec Software. I implemented **polyphony** and preset manager. |       |
| [synthv1](https://github.com/AnClark/synthv1-universal)      | An old-school polyphonic synthesizer by rncbc. Port to DPF   |      |
| [padthv1](https://github.com/AnClark/padthv1-universal)      | an old-school 4-oscillator subtractive polyphonic synthesizer, by rncbc. Port to DPF |      |
| [zyn-fusion-build](https://github.com/AnClark/zyn-fusion-build) | Enhanced build script for ZynAddSubFX, a powerful FOSS synthesizer |      |

#### Classic Series Reborn

I also reverse-engineered **Kjaerhus Classic Series**, a well-known free VST bundle by Kjaerhus Audio, bringing the deprecated but legendary masterpieces to life in 2026. Originally they are legacy 32-bit, Windows-only VST2 plugins in early-2000s. Now they are cross-platform and work well on modern 64-bit platforms, with a preset manager.

- **Classic Reverb RE**: 4 flavors of implementations ([RE-01](https://github.com/AnClark/ClassicReverb-RE01), [RE-04](https://github.com/AnClark/ClassicReverb-RE04), [RE-03](https://github.com/AnClark/ClassicReverb-RE03), [RE-02](https://github.com/AnClark/ClassicReverb-RE02))
- **Classic Flanger RE**: 2 flavors of sound ([RE-01](https://github.com/AnClark/ClassicFlanger-RE01), [RE-02](https://github.com/AnClark/ClassicFlanger-RE02))
- **[Classic Chorus RE-01](https://github.com/AnClark/ClassicChorus-RE01)**
- **[Classic Master Limiter RE-01](https://github.com/AnClark/ClassicMasterLimiter-RE01)**

### Former projects

<details>
  <summary>Click for more details</summary>

### Android/TWRP port

| Project                                                      | Introduction                                                 | Note                       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------- |
| [TWRP Device Tree for Huawei P6](https://github.com/AnClark/device_huawei_hwp6_u06) | Build TWRP 3.x for Huawei Ascend P6. Support newer features in Omni 8.1 (FunctionFS, SELinux, etc.). | Use branch `omni-8.1-twrp` |
| [kernel-huawei-p6](https://github.com/AnClark/kernel-huawei-p6) | Kernel for Huawei Ascend P6.<br>I backported some features to this 3.0.x kernel. For example, SELinux policydb ver. 30, FunctionFS support.<br>This helps building TWRP with Omni 8.1 (or possibly newer). |                            |
| [TWRP Device Tree for Huawei B199](https://github.com/AnClark/twrp_device_huawei_g750c) | Build TWRP 3.x for Huawei B199. Support newer features in Omni 8.1 (FunctionFS, SELinux, etc.). |                            |
| [kernel-huawei-msm8628](https://github.com/AnClark/android_kernel_huawei_msm8628) | Kernel for Huawei B199.<br>I backported FunctionFS there, so it can support ADB and MTP on Android 8.1. |                            |

### Improvements for applications

| Project                                                 | Instruction                                                  | Note           |
| ------------------------------------------------------- | ------------------------------------------------------------ | -------------- |
| [DesktopNaotu](https://github.com/AnClark/DesktopNaotu) | My fork of DesktopNaotu, the desktop version of Baidu Naotu (mindmap). This version introduces many improvements. | Not maintained |
| [MarkText](https://github.com/AnClark/marktext)         | I implemented i18n support for MarkText, with my full Simplified Chinese translation, based on vue-i18n. <br>I submitted a PR, but the maintainer didn't accept my patches. |                |

### PKGBUILDs

| Project                                                      | Instruction                                                  | Note |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- |
| [LoongArch cross GCC](https://github.com/AnClark/loongarch64-linux-crosstool-gcc-PKGBUILD) | Build LoongArch cross-compilers on Arch Linux. Based on [Jiege's blog](https://jia.je/software/2022/05/02/loongarch64-toolchain/). |      |
| [Static Qt6 for Msys2](https://github.com/AnClark/msys2-qt6base-static) | Build Qt6 static library for Msys2.                          |      |

### Updates

| Project                                                      | Instruction                                          | Note |
| ------------------------------------------------------------ | ---------------------------------------------------- | ---- |
| [Yilia (AnClark customized)](https://github.com/AnClark/anclark-yilia-theme-customized/) | Hexo Yilia theme. I migrated the theme to Webpack 5. |      |
| [Yilia Plus](https://github.com/AnClark/hexo-theme-yilia-plus/) | Yilia plus theme. I migrated to Webpack 5 as well.   |      |

</details>

## Contributions

- DPF (DISTRHO Plugin Framework):
  - Add external UI support for CMake ([commit](https://github.com/DISTRHO/DPF/commit/a338aa6559c8d8d79d0e062f6a2963f511c667c0))

- Vee-One Suite (synthv1, padthv1, etc.)
  - Add Win32 LV2 support ([contributions](https://github.com/rncbc/synthv1/commits?author=AnClark))
- TWRP
  - Mi Max Prime: Add initial QSEE decryption support
  

