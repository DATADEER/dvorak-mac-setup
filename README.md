# Dvorak Mac Keyboard setup
This setup helps to seamlessly switch between the QWERTZ and DVORAK Layout

## Setup US Keybaord Layout

1. Launch `System Preferences` under the Apple menu, go to the `Keyboard Preferences` pane, and select the `Input Sources` tab.
2. Click on the `+` in the lower left corner. In the overlay, select `English`, then the `U.S.` via Option Key keyboard layout. Click `Add` to close the overlay.
4. You can now select `U.S.` from the flag symbol in the menu bar.

## Dvorak CMD-QWERTY Switch Layout for Karabiner Elements

1. Install `Karabiner Elements` from https://pqrs.org/osx/karabiner/
2. Create 2 Profiles inside `Karabiner Elements`
    1. `QWERTZ`
    2. `DVORAK`
3. Install the `Dvorak-CmdQwerty Keyboard` complex modification either by copying `dvorak-mac-setup/KarabinerElements/dvorak-cmd-qwerty.json` into `~/.config/karabiner/assets/complex_modifications` or by importing it from https://pqrs.org/osx/karabiner/complex_modifications/#dvorak_cmd_qwerty_layout
4. Switch to the `DVORAK` profile
5. Enable the `Dvorak-CmdQwerty Keyboard` rule while being on the `DVORAK` profile

## Quick Switch Profile and Layout with Alfred3

1. Install Alfred3 from `https://www.alfredapp.com/`
2. Import the Workflow from `dvorak-mac-setup/Alfred/SwitchLayoutWorkflow`
3. Adjust Profile names or Keyboard Layout names in `dvorak-mac-setup/Alfred/SwitchLayoutWorkflow/set.py` if necessary
4. Use the alfred command `111` to switch between profiles

## Add support for umlaut modifier key
1. Install the `Umlauts` complex modification by copying `dvorak-mac-setup/KarabinerElements/umlauts.json` into `~/.config/karabiner/assets/complex_modifications`
2. Enable the `Umlauts` complex modification for the `DVORAK` Profile inside `Karabiner Elements`
