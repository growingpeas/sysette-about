# Sysette

**A preset librarian and editor for MIDI synths and pedals, in your browser.** Plug your instrument in,
open [sysette.com](https://sysette.com) in Chrome, Edge or Opera, and read every preset in one go.
Nothing to install, nothing uploaded.

The first supported instrument is the **Sequential Take 5**; more synths and effects pedals are being added.
Write to info@sysette.com to ask for yours.

## Free: the librarian

- Read one bank or the whole memory from the instrument into a searchable library kept in your browser.
- Import and export standard `.syx` files: Sequential's factory banks, packs you bought, your own backups.
- Send banks back. Every write is confirmed first, then each preset is read back and compared byte for byte
  before the next one goes out.
- The panel view: pick a preset and see where every knob sits, following the instrument live.

## Full version, US$29 once

- The panel editor: turn every knob and switch from the screen, live on the instrument.
- The memory plan: drag presets between memory locations, then send the result.
- Rename, duplicate and save edited variants.
- Calibrate, to map the parameters of your own unit.
- Every instrument Sysette adds later, included.

On the Take 5, parameter ranges are measured on a real unit running firmware 2.2, not copied from the MIDI
implementation chart, which is wrong on several of them.

## Requirements

A desktop browser with Web MIDI and SysEx: Chrome, Edge or Opera. The instrument over USB, or over DIN through
any MIDI interface. On Linux, SysEx messages over 4 kB need a larger `snd-seq-midi` buffer; the app shows the
command when it detects the problem.

---

Sysette is independent and not affiliated with Sequential. Synth names are trademarks of their owners.
Published by Growing Peas. Questions: info@sysette.com.
