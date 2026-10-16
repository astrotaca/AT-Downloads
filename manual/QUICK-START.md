# AstroTaca Flat Panel · Quick start

**Pre-release draft · Windows software 3.2.2**

The product is still in development. No public installer is available yet.
Use the confirmed mounting instructions and approved power supply for your unit;
final product specifications are still pending.

## 1. Install and connect

1. Once available, download Setup from [AstroTaca Releases](https://github.com/astrotaca/AT-Downloads/releases).
   Close NINA and AstroTaca windows, then run Setup. Approve the administrator
   prompt when asked.
2. If Setup asks, choose **Install ASCOM Platform** and follow its window.
   AstroTaca Setup continues when ASCOM is ready.
3. Connect the panel with a **USB data cable** and its approved **12 V DC supply**.
   USB alone cannot power movement or light. Keep the cover's path clear.
4. Open **AstroTaca Flat Panel** from Start or the desktop. If asked, choose its
   **USB port** and **Save**, then choose **Connect**. The port is remembered.
5. If calibration is requested, follow [the calibration guide](README.md#set-closed-and-open-positions)
   before using the controls. Check the actual Closed and Open positions with
   the movement area clear.

## 2. Choose your controls

**In the AstroTaca app:** choose **Close** and wait for **Closed**. Select a low
brightness with the slider, then choose **Turn on / apply**. Moving the slider
alone does not change the light. Choose **Light off** when finished.

**In NINA:** go to **Equipment → Flat Panel**, select **AstroTaca Flat Panel
(ASCOM)** and connect. Its settings gear lets you choose the USB port. Choose
**Close**, wait for **Closed**, then enter your brightness and choose **Set**.
Use NINA's light control to switch it off when finished.

**Close first, then light on.** A light request never closes the cover for you.
Opening switches the light off. The two apps can share a connection; disconnecting
only the AstroTaca app leaves NINA connected. Keep manual controls idle during
an automated sequence.

## 3. Use the button

| Press | Result |
|---|---|
| Quick tap | Open or close; stop if already moving. |
| Hold about **1 second, then release** | While Closed: **Off → Dim → Medium → Bright → Off**. |
| Hold **3 seconds** | Stop and turn the light off while still holding. |

While Closed, use the app's **Button settings** to set your three levels and
choose **Save to panel**. **Dim is your usual starting brightness.** Presets stay saved without
power and work without a computer. Powering on does not turn on the light.

**The motor does not keep holding the cover after a move or Stop. Make sure it
is supported so it cannot fall. Keep hands clear during powered movement.**

[Full manual, opening limits and troubleshooting](README.md) ·
[Ask for help](https://github.com/astrotaca/AT-Downloads/issues)
