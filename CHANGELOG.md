# Changelog

## v1.4

> _16th November 2020_

- 🚌 Bus Driver

  - 📈 (Bus Driver) Spreadsheet now use ARRAYFORMULA across fields that repeat the same formula
    > This includes Boost calculation (using sheet matrix) and calculated earnings on reverse EXP
    
  - 🚧 Error handling on this new adaptation now returns an empty string
  
  - 🚏 Stop data has been extracted and parsed based on the server configurations
    > Though this may provide an additional metric, it does not narrow the angle on how the reward can be calculated outside of its native environment

## v1.3

> _31st July 2020_

- 🚁 Helicopter Pilot

  - 📒 Created Bulk Data Template

- 🚌 Bus Driver

  - 🏷 Patched `Data Validation` dropdown for Server column on Bulk Data Template

> _1st August 2020_

- 🚌 Bus Driver

  - 📭 Cleared responses from Form cache

## v1.2

> _31st July 2020_

- 🚁 Helicopter Pilot

  - 🎉 Accepting responses
  - ♻ Reverse calculation in place for boosts and tokens

- 🧩 Form handling (✈ Airline Pilot, 🚌 Bus Driver)

  - ⛔ No longer accepting edits for individual records (Driver Credit remains as is)
  - 🗑 Removed fields and information related to record edits.

## v1.1

> _30th July 2020_

- ✈ Airline Pilot

  - 🎉 Accepting Responses
  - 🗑 Removed EXP related questions

## v1.0

> _30th July 2020_

- 🚌 Bus Driver

  - 📦 Now allows auto data processing through a status cell.
  - 📥 Data is now processed and imported automatically.
  - 🧮 Reverse EXP calculation is now in full effect based on the boosts submitted with the route.
  - 🚏 Known failures have moved to the Info sheet.
  - 📂 A filter view has been created on the (Auto) sheet.

- ✈ Airline Pilot

  - 🗑 Data input will no longer require EXP data.
