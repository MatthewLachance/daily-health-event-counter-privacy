# Help – Daily Health Event Counter App for Android

## Quick Start
- Tap **+** to record a health event
- Use the **Today** (date picker) button to view or edit past days
- Tap **History** to see trends
- Each day at midnight, the event count clears after saving previous day

## About the App

Ideal for monitoring symptoms, habits, or medical tracking between appointments.

Key Features:
- One-tap event tracking throughout the day
- Automatic daily reset with history preserved
- View trends over time with built-in history line graph
- Review and edit past days easily
- Big buttons for easy over night use
- Export data for backup or to paste into spreadsheet
- Import CSV file to load the app with historical data
- Export then Import when changing phones
- Works offline — no account required
- No data sharing — your information stays on your device
- App languages: English, français

Use Cases
- Track daily symptoms (bathroom visits, pain, headache frequency, etc.)
- Monitor habits or recovery progress
- Provide accurate data to healthcare providers
- Or just count things (with daily history)

This app is ideal for personal tracking and for sharing accurate data with healthcare professionals when needed.
All data is saved locally on your phone.

## How to Adjust Daily Counter

- Tap **+** to add one to the counter
- Tap **-** to reduce the counter by one
- Use **reset** to set the counter back to zero (confirmation required)
- Use **clear** to set a no-data-recorded state (confirmation required)

*Note:* 
- The counter automatically clears when a new day starts (midnight). Your previous day counter value is saved for use in observing trend (history).

## How to View History ##

- Tap the History button to view a trend of events over time
- The graph shows the total event values (y-axis) on a daily basis (x-axis)

*Notes:*
- The graph may be best viewed in landscape mode (rotate your phone)
- A minimum of two recorded days is required before a graph is rendered

## Pro Features
<!-- Anchor target -->
<a id="pro-features"></a>

The following features may require an upgrade to the Pro tier.

- Edit past days
- Export data (CSV)
- Import data

## How to View or Edit Past Days ##

- Tap the **Today** button and pick a past day to view
- Tap that same button to return to the current day (or to view a different day)
- To edit a past day, first view it as above then tap the pencil icon
- Use the various buttons to adjust the event count for the past day

## How to Export ##

Use Export to backup your historical data. For privacy reasons, data is not stored on servers. 

Why backup? In the situation where you change phones or you accidently clear the app data via Android settings, the history will be erased. Periodically using Export to save history is a good practive.

Tapping Export will ask you share a CSV (comma separated values) file with some other app on your phone. The best choice for backup is to share to your Google Drive app. Google Drive data is automatically saved in your private Google account on servers.

Alternatively, you may wish to share with an email app (e.g. Gmail) and send the CSV file as an attachment to yourself. This effectively saves your data on servers too. 

Watch this video to see how to effectively backup your history by exporting to email. ***** TODO link to Youtube *****

*Advanced Usage:*

The exported CSV file can also be used to load into a spreadsheet program such as Google Sheets or Microsoft Excel. This will allow you to integrate with other data and/or build more complex charts and graphs.

The format of the contents of the CSV file is simple:

date,count
YYYY-MM-DD,nn
...

The first row the CSV file are headers "date,count" and each row thereafter will represent the event count for a given date.

## How to Import ##

Import supports recovery and loading trend data. Use Import to recover previously backed up event counts or to load historical daily event counts from another source. 

The format of the file expected by Import is the same as described above for Export (see above).

## FAQ

**What's the difference between resetting the counter for the day and clearing the counter for the day?**

In the case of a reset, the counter goes to zero. Zero health events for the day may be meaningful. In the case of clear, there is no data recorded for that day (until you tap the **+**). For history (trending) it may be important to distinguish between days you have had zero events verus days that you decided not to record anything.


