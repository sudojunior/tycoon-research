## Additional Considerations (Bus Driver)

- Gather coordinates for each bus stop.
- Collaboration between multiple drivers (drive-in pairs. one drive a route, the other follows behind and sets waypoints to the next stop to calculate distance using GTA's navigation).
- ~~Include weather conditions/time of day~~
- [x] Allow for bulk input? If drivers complete multiple routes and want to submit it all at once, I recommend creating Google Sheet or Excel file with column headers for:
  - Timestamp (Date & Time)
    - Start? (currently not an input option)
    - End
  - Duration (if you have that, if not don't worry - consider it as extra)
  - Server (i.e. OS-1, EU-2)
  - Vehicle (i.e. Liberty City Bus, Tour Bus - vehicle display name)
  - Route (i.e. R3, C1 - route number)
  - Fare Count \*1
  - Earnings \*1
  - Experience \*1
  - Notes (not required, but any trip notes that you think would be useful)

\*1: An alternative would be to create screen captures after each route is completed, any software that attaches timestamps to images is perfectly fine and then have some document that notes down which picture is (route, vehicle, server, etc.).