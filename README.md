# Sysette

**A preset librarian and editor for the Sequential Take 5, in your browser.** Plug the synth in, open
[sysette.com](https://sysette.com) in Chrome, Edge or Opera, and read all 256 user programs in one go.
Nothing to install, nothing uploaded.

## Free: the librarian

- Read one bank or all sixteen from the synth into a searchable library kept in your browser.
- Import and export standard `.syx` files: Sequential's factory banks, packs you bought, your own backups.
- Send banks back. Every write is confirmed first, then each program is read back from the synth and compared
  byte for byte before the next one goes out.

## Full version, US$29 once

- The panel editor: every knob and switch of the Take 5 on screen, edited live, values read from the program.
- The memory plan: drag programs between the 256 user locations, then send the result.
- Rename, duplicate and save edited variants.
- Calibrate, to map the parameters of your own unit.

Parameter ranges are measured on a real Take 5 running firmware 2.2, not copied from the MIDI implementation
chart, which is wrong on several of them.

## Requirements

A desktop browser with Web MIDI and SysEx: Chrome, Edge or Opera. The Take 5 over USB, or over DIN through any
MIDI interface. On Linux, SysEx messages over 4 kB need a larger `snd-seq-midi` buffer; the app shows the
command when it detects the problem.

---

Sysette is independent and not affiliated with Sequential. Synth names are trademarks of their owners.
Published by Growing Peas. Questions: info@sysette.com.
