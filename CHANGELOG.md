# Changelog

The live version shows next to "Schematic Builder" in the top bar; click it for this list.

## v1.10 – 2026-11-17
- Schedule Detail and the Excel file list layers Primary first (smaller primaries first), then by attachment, lowest to highest
- Filter the Schedule Detail by carrier or notes, access point, status or layer; matching boxes stay bright in the schematic and the rest fade (exported images are never faded)
- "–" instead of $0 premium when a schedule has no premiums

## v1.9 – 2026-11-17
- Import on top: new tables, pastes and text lines are added to the schematic on screen (e.g. to add a layer), instead of replacing it
- Choose "Add to current schematic" or "Replace it" at the top of the Import tab; Add is the default

## v1.8 – 2026-11-17
- Copy Image and Download PNG include the program name, limit, premium, TIV, rate and date at the top and the legend at the bottom, and are always in the light theme
- TIV box under the program name: shows the rate per $100 of TIV for the program and each layer; read automatically from a "TIV: …" title row or a "TIV $5.87B" text line, and saved with the program and in the Excel file
- Warnings fold into one line of chips, with Details to see each one
- Open space is a soft grey hatch instead of red
- Combine Repeat Carriers: one box per carrier per layer (shows when a carrier has more than one line on a layer)
- Asks before switching programs or leaving the page with unsaved changes
- Removing a line can be undone
- Download Excel shows a dot when programs have been saved since the last download
- Headline figures are a compact strip; the right-hand column is labelled; lighter grey for markets with no access point

## v1.7 – 2026-11-17
- Readable layout has no empty gaps: every layer fills the full width, so it's always a clean rectangle
- Edit the schedule in place: click any cell (carrier, share, line, premium, 100% premium, status, notes), add a carrier to a layer, add a layer, or remove a line
- Schematic and Import are now separate tabs; loading a file, a paste, the sample or a saved program goes straight to the schematic
- Quick Add Text keeps names like "Lloyd's of London" and "Liberty Specialty Markets Bermuda Limited" whole
- A schedule with no premiums shows one note instead of a warning per layer

## v1.6 – 2026-11-17
- Quick Add Text takes the layer on the same line: "Chubb 10% of Primary $30M", "AIG 2.5% of $50M xs $50M", "Zurich 15% of $30M"
- One carrier on several layers in one line: "Beazley 10% of Primary $30M, 5% of $20M xs $30M"
- Also understands "$30M primary", "$20M x $30M" and "p/o"
- Names like "Beazley / Lloyds" keep the "Lloyds" (and count as London)

## v1.5 – 2026-11-17
- New Readable layout: every carrier the same width so names fit, and every layer fills the full width as a clean rectangle
- In Readable, a carrier on several layers keeps one column all the way up; open space gets a column of its own
- Readable boxes show share and line, the carrier's premium for their share, and the 100% layer premium
- Hover any box for its line, premium for their share and 100% layer premium
- Long names wrap onto up to three lines; a wide Readable schematic scrolls sideways and prints to fit the page

## v1.4 – 2026-11-17
- Overlapping layers (e.g. carriers on P$25M, P$50M and P$75M) are split into stacked layers; a carrier on a bigger layer is one block running through every layer it covers
- Open space, placed % and premium are worked out for each of those layers
- Columns are checked by what they hold: a $ "Participation" column is read as the line, and a % column as the share
- Notes and blank rows under the schedule are ignored
- Colour by access point is the default again; markets with no access point are all grey
- Carriers named "… / Lloyds" count as London and "… Bermuda …" as Bermuda when no access point is given
- Narrow blocks show the carrier name sideways

## v1.3 – 2026-11-17
- Version number in the top bar; click it to see the version history

## v1.2 – 2026-11-17
- Save several programs and switch between them from the top bar
- Download Excel: one sheet per saved program, with every figure filled in; load the file to bring them all back
- Line $, share, premium and 100% premium are worked out when missing and shown in blue italics
- ART and Terrorism access points; Direct is now indigo so it doesn't look like London; no access point stays grey

## v1.1 – 2026-11-17
- Upload an Excel or CSV schedule and match its columns
- New look, light and dark themes, access point colours

## v1.0 – 2026-11-17
- First version: paste a schedule and see the tower
