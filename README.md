# MotionSync VR

# MotionSync is in Beta, please expect it to be buggy.

**MotionSync VR** is a Python-based tool that turns Nintendo Joy-Con™️ motion input into simulated VR controller input. Play VR-compatible games like SteamVR and Roblox using Joy-Cons — no headset required.

## Features

- Joy-Con motion emulation (gyro + accel)
- Customizable layouts for Meta Quest, Valve Index, and HTC Vive
- PyQt5 debug interface
- SteamVR-compatible input via virtual devices

## Requirements

- Windows 10/11
- Python 3.10+
- Joy-Cons connected via Bluetooth
- ViGEmBus installed (https://github.com/ViGEm/ViGEmBus)
- SteamVR (optional)

## Installation

```bash
git clone https://github.com/skilldGT/MotionSyncVR.git
cd MotionSyncVR
pip install -r requirements.txt
python main.py
```

## Usage

1. Run `main.py`
2. Connect your Joy-Cons via Bluetooth
3. Select your preferred controller layout
4. Launch a compatible game

## License

MIT License  
Not affiliated with Nintendo or any VR platform.
