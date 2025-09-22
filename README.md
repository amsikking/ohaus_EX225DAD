# ohaus_EX225DAD
Python device adaptor: Ohaus Explorer Semi-Micro Balance EX225D/AD
## Quick start:
- Connect to the balance using the hidden **USB Mini-B** port under the touch screen.
- The generic FTDI driver installed by Windows seems to work fine.
- Find the 'COM' port and then download and run 'ohaus_EX225DAD.py' for basic Python interaction.

**Note:** if you're going to programmatically open the doors make sure there is enough space behind!

![social_preview](https://github.com/amsikking/ohaus_EX225DAD/blob/main/social_preview.png)

## Details:
- This minimal device adaptor was generated using the included 'Manual_Explorer_Semi-Micro.pdf' (page EN-158).
- There is some confusion about what commands are actually available ('Interface Commands' vs 'USB INPUT') and what the response should be ('USB OUTPUT'?) so some trial and error was needed to get the basic functionality.
