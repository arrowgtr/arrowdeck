# ArrowDeck Pro 🎯⚡
### The Futuristic, Context-Aware Radial Action HUD for Windows

> **ArrowDeck** transforms your mouse and keyboard workflow with an ultra-responsive, context-aware radial action deck. Hold your right mouse button or tap `Alt + Space`, flick toward any direction, and execute commands instantly through pure muscle memory.

---

## ⚡ What is ArrowDeck?

Traditional menus and hotkeys force you to look down at your keyboard or hunt through nested context menus. **ArrowDeck** puts your most important tools and shortcuts directly around your cursor in an ergonomic 8-direction radial HUD.

- 🧠 **Context-Aware App Morphing**: Automatically detects your active application (Brave, Chrome, Photoshop, VS Code, File Explorer, NordVPN, Discord, Viber, etc.) and seamlessly switches to dedicated rings tailored for that app.
- ⚡ **Zero-Latency Flick Gestures**: Move the mouse slightly toward a slice and release to fire the action in under 80 milliseconds.
- ⭕ **Orbiting Satellite Bubbles (Sub-Rings)**: Nested actions float outward into beautiful orbital bubbles.
- 🛡️ **NordVPN Real-Time Hub**: Live connection telemetry right in the center hub (status and active country), plus 1-click connect, reconnect, specialty servers, and country switcher.
- 🤖 **AI Smart Text & Gemini AI**: Instant AI text summarizer, grammar corrector, translation across 8 languages, bullet points formatter, and code explainer.
- 🎨 **30+ Cyberpunk & Luxury Themes**: Built-in HUD visual themes with full per-profile color customization for slice fills, glowing borders, text labels, and icon glyphs.

---

## 🚀 Quick Start & How to Launch


Double-click `ArrowDeck.exe`. ArrowDeck immediately starts quietly in your Windows system tray.


## 🎮 How to Use ArrowDeck (User Tutorial)

### 1. Summoning the Radial HUD
You can summon your radial deck anywhere on Windows:
- **Mouse Hold**: Hold down the **Right Mouse Button** for ~220ms. The ring appears centered at your cursor.
- **Keyboard Shortcut**: Press **`Alt + Space`** anywhere to summon the HUD immediately.
- **Flick & Release**: Move your cursor toward the desired slice (North, NE, East, SE, South, SW, West, NW) and release.
- **Cancel**: Release at the center hub or press **`Escape`** to dismiss without triggering any action.

### 2. Navigating Satellite Bubbles (Sub-Rings)
Slices with child actions display a small capsule indicator:
- When you hover over a slice with sub-actions, glowing laser beams extend outward and **orbiting bubble nodes** appear.
- Flick your cursor directly onto an orbital bubble to execute that specific sub-action!
- Or click the parent slice to drill down into the full sub-ring (the center hub shows a `⬅ Back` button to return).

### 3. Mouse Wheel Superpowers
Hovering your cursor over certain slices enables instant scroll wheel shortcuts:
- **Over Volume / Media slice**: Scroll Up / Down to adjust system master volume in 2% increments.
- **Over Browser / Tab slice**: Scroll Up / Down to cycle through browser tabs (`Ctrl+Tab` / `Ctrl+Shift+Tab`).
- **Over Zoom slice**: Scroll Up / Down to zoom in / out (`Ctrl++` / `Ctrl+-`).

### 4. Keyboard Navigation
ArrowDeck is 100% operable from your keyboard:
- **1 – 8 Number Keys**: Directly triggers slice 1 through 8.
- **Arrow Keys**: Joystick directional navigation around the ring.
- **Type-to-Find**: Typing the first letter of a slice title instantly selects it.
- **Enter / Space**: Executes the currently selected slice.
- **Escape**: Closes the ring safely.

---

## 🛠️ Customizing Your Radial Rings

ArrowDeck features a powerful visual **Settings & Ring Editor GUI**:

### 1. Replacing & Adding Slices via the Action Catalog
1. Open the Settings window from the tray icon or by running `python main.py --settings`.
2. Select your active profile (e.g., *Everyday*, *NordVPN*, *Browsers*, *Photoshop*).
3. Click any slice directly in the **Live HUD Simulator** or click **⚡ Replace Slice (Open Catalog)...**.
4. The **Action Catalog** opens with 200+ power features organized into categories:
   - 🎯 **Current Profile Slices**: Shows all slices currently configured on this ring, allowing you to easily swap, move, or duplicate slices to any direction.
   - 🛡️ **NordVPN**: Quick Connect, Disconnect, Reconnect, Countries Hub, P2P Servers, Obfuscated, Double VPN, and direct country links.
   - ⭐ **Top 10**: Instant 1-click essentials (AI Smart Text, Screen Snip, OCR, Terminal Here, Always-on-Top, Empty Bin, Dark/Light Mode).
   - 🌐 **Browsers**: New Tab, Restore Closed Tab, Incognito, Bookmarks, History, Downloads, DevTools.
   - 📁 **File Tools**: Terminal Here, LocalSend wireless sharing, Zip/Unzip, Image Converters (PDF, PNG, JPG, WebP), Clean EXIF metadata.
   - ⚡ **System / Media**: Audio mute, volume sliders, media playback, monitor switcher, PC power controls.
   - ⭕ **Sub-Rings**: Nested orbital bubble hubs.
   - ✏️ **Custom Action Builder**: Create your own keyboard shortcuts, shell scripts, or application launchers.
5. Use the real-time search bar to filter instantly with **zero flicker**!

### 2. Customizing Per-Profile Colors (Themes & Icons)
Want your NordVPN ring to shine in electric blue, your Photoshop ring in cyan, or your Spotify ring in neon green?
1. Check **Enable Custom Colors for this Ring Profile**.
2. Pick any color for:
   - **Ring Background Fill**: Deep space dark or slate floor.
   - **Accent Glow & Highlight**: The active glowing slice and hub border color.
   - **Border & Divider Lines**: Radial rim and slice separator lines.
   - **Text Labels Color**: Typography of slice titles.
   - **Icon Glyphs Color**: Precise vector color for all icons on the ring.
   - **Center Hub Background**: Center circle styling.
3. The **Live HUD Simulator** on the right reflects your exact color choices in real-time!

### 3. Assigning Trigger Applications
In the **Trigger on Apps** input box, list the executable process names separated by commas (e.g. `nordvpn.exe, nordvpnapp.exe` or `photoshop.exe` or `chrome.exe, brave.exe, msedge.exe`).
Whenever that application is brought to the foreground, ArrowDeck automatically switches to that ring profile!

---

## 🛡️ NordVPN Live Telemetry & Quick Control

ArrowDeck includes native background integration with the official Windows **NordVPN** CLI:
- **Live Status in Center Hub**: The center hub actively monitors NordVPN's status and displays `CONNECTED: Germany` (or your active country) in glowing green, or `DISCONNECTED` in gray.
- **Quick Connect (`zap` icon)**: Instantly joins the fastest optimal server.
- **Disconnect (`lock` icon)**: Safely shuts down the VPN tunnel.
- **Reconnect (`refresh` icon)**: Automatically disconnects and re-establishes a fresh secure tunnel.
- **Specialty Servers**:
  - `P2P Torrent Servers` (`download` icon)
  - `Obfuscated Servers` (`shield` icon) — bypasses firewalls, hotel blocks, and ISP throttling
  - `Double VPN` (`shield` icon) — multi-hop dual encryption
- **Countries Orbital Sub-Ring (`flag` icon)**: 8 satellite bubbles for United States, United Kingdom, Germany, France, Japan, Canada, Switzerland, and Netherlands.

---

## 🤖 AI Smart Text & Google Gemini AI

Supercharge your reading and writing anywhere on Windows:
1. Select any text in any document, browser, or editor, and summon ArrowDeck.
2. Select **Smart Text**:
   - **Summarize**: Condenses articles or emails into key takeaways.
   - **Fix Grammar**: Cleans up typos, commas, and spelling without changing your meaning.
   - **Translate**: Subring for English, Spanish, German, French, Japanese, Chinese, Italian, Portuguese.
   - **Bullet Points**: Reformats messy paragraphs into structured lists.
   - **Explain Code**: Breaks down code syntax and logic into plain English.
   - **Professional Tone**: Rewrites informal thoughts into polite corporate correspondence.

---

## 🪟 Windows Snapping & Window Management

Snap and arrange windows with a single mouse flick:
- **Snap Left / Right**: Tiles the active window to the left or right 50% screen edge.
- **Maximize / Minimize / Center**: Instantly sizes or centers the window.
- **Pin Always on Top**: Prevents the active window from being covered by other apps.
- **Window Switcher**: Dynamically lists running desktop apps as slices so you can flick-switch between windows.

---

## ⌨️ Hotkeys & Gesture Cheat Sheet

| Gesture / Key | Action |
| :--- | :--- |
| **Right Mouse Button (Hold ~220ms)** | Summon Radial HUD at cursor |
| **Alt + Space** | Summon Radial HUD anywhere |
| **Flick toward Slice + Release** | Execute selected slice action |
| **Flick onto Outer Satellite Bubble** | Execute orbiting sub-action |
| **Scroll Wheel over Volume Slice** | Adjust System Master Volume (±2%) |
| **Scroll Wheel over Browser Slice** | Switch to Next / Previous Browser Tab |
| **1 – 8 Keys** | Trigger Slice 1 to 8 instantly |
| **Arrow Keys** | Navigate slices directionally |
| **Escape Key** | Close Radial HUD without action |

---

## 📦 Building from Source (Compiling the EXE)

To build a standalone single-file `ArrowDeck.exe` with the rimmed radial icon embedded:
```bash
python -m PyInstaller arrowdeck.spec --clean -y
```
The compiled executable will be placed in the `dist/` directory.

---

## 💡 Frequently Asked Questions (FAQ)

#### Q: Why doesn't ArrowDeck trigger over certain administrator or game windows?
**A**: Windows security (UAC / UIPI) prevents non-elevated background apps from hooking or typing into administrator windows. If you want ArrowDeck to work over Task Manager, Registry Editor, or elevated games, simply run ArrowDeck as Administrator!

#### Q: Does ArrowDeck run silently in the background?
**A**: Yes! When launched via `ArrowDeck.exe`, ArrowDeck creates zero console windows and sits quietly in your system tray using under 0.1% CPU.

#### Q: How does single-instance protection work?
**A**: ArrowDeck uses a named Windows mutex and PID lock file (`Local\ArrowDeck_SingleInstance_Mutex_v1`). Launching a new instance gracefully replaces an older instance so you never have duplicate conflicting mouse hooks.

---

## 📄 License
MIT License. Created with ❤️ for lightning-fast Windows productivity.
