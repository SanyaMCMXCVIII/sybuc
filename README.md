# sybuc
**BeatUp Converter from SM to SLK and vice versa**: Public Version

---

This program was designed to convert **StepMania** files into **Sylk** files for **Audition Online**.
The main logic for this program is to create **BeatUp Charts**.

---

## Video Guide

[Video Guide (YouTube)](<https://youtu.be/OhK-tpzQR10>)

---

## About the Program

This program was written in **Python** and might not work on every computer.

A console will pop up when opening this tool, including a **Browse-File Dialog**. Please select your StepMania file and click on "Ok". A new Sylk file will be created in your **output folder**. Metadata of your Chart will be shown in the Console. Close the console with the **Enter** key.

---

## Key Logic

The conversion follows this mapping:

| Arrow Vortex (SM) | Excel (SLK) | Notes |
| :---: | :---: | :--- |
| `1` | `7` | Standard Left-Middle |
| `2` | `4` | Standard Up-Left |
| `3` | `1` | Standard Up-Right |
| `4` | `9` | Standard Down-Left |
| `5` | `6` | Standard Down-Right |
| `6` | `3` | Standard Right-Middle |
| `7` | `Random` | Random Key array {1,4,7,3,6,9} |
| `8` | `Space` | Space |
| `M` | `Finish Move` | Mine on 8 key |
| `1 + 7` | | Random key on the **left side** |
| `2 + 7` | | Random key on the **right side** |
| `7 + 8` | | **Empty Finish Move** (no space) |
| `1 - 6 + 7 + 8` | | **Empty Finish Move** + note |

---

## Copyright & Last Update

Copyright **Sanya**, April 2025.
Last Update: September 30th, 2025.
