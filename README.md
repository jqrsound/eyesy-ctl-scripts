# eyesy-ctl-scripts


![OS](https://img.shields.io/badge/OS-Patchbox%20OS-blue)
![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi-red)
![Audio](https://img.shields.io/badge/Audio-Blokas%20PiSound-purple)
![Synth](https://img.shields.io/badge/Video%20Synth-EYESY-orange)

## Pisound App scripts for EYESY

A collection of scripts to use Eyesy with the Pisound mobile App.  
The Pisound App connects to a dedicated server called `pisound-ctl`, which can list and launch scripts, making it easier to browse, launch, and manage EYESY patches. 

## Requirements

- Raspberry Pi with Pisound installed.
- `pisound-btn` version 1.05 or higher.
- `pisound-ctl` version 1.03 or higher.
- Bluetooth support on the Raspberry Pi.

## Installation

Clone this repository and place the scripts  under `/usr/local/pisound-ctl/`

```bash
git clone https://github.com/jqrsound/eyesy-ctl-scripts
```

## Related projects

- [EYESY OS for RasPiSound](https://github.com/jqrsound/EYESY_OS_for_RasPiSound)