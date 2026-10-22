# Hex Dump Text File Viewer

A browser-based tool that converts any text input into a byte-by-byte hex dump displayed in the classic xxd/hexdump style, with offset addresses, hex bytes, and an ASCII panel side by side.

## Features

- Paste or type any text to instantly see its hex representation
- Toggle between UTF-8, ASCII (7-bit), and Latin-1 (ISO-8859-1) encoding modes
- Classic xxd-style columns: offset | hex bytes | ASCII panel
- Configurable bytes-per-row: 8, 16, or 32
- Color-coded byte highlighting: null bytes (red), non-printable control characters (yellow), high bytes above 0x7F (purple), printable ASCII (green)
- Toggle highlighting on/off
- Live byte count display
- Dark terminal aesthetic for comfortable viewing
- Handles Unicode multi-byte sequences correctly in UTF-8 mode
