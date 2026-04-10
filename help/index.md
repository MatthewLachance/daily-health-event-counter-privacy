# Help – Daily Health Event Counter App for Android

## Quick Start
- Tap **<span style="font-size: 24px;">+</span>** to record a health event
- Use the **Today** (date picker) button to view or edit past days
- Tap **History** to see trends
- Each day at midnight, the event count clears after saving previous day

## About this App

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

- Tap **<span style="font-size: 24px;">+</span>** to add one to the counter
- Tap **<span style="font-size: 24px;">-</span>** to reduce the counter by one
- Use **Reset** to set the counter back to zero (you’ll be asked to confirm)
- Use **Clear data** to remove all entries for this day (you’ll be asked to confirm)

*Note:* 
- The counter automatically clears when a new day starts (midnight)
- Your previous day counter value is saved for use in observing trend (history).

## How to View History ##

- Tap the **History** button to view a trend of events over time
- The graph shows the total event values (y-axis) on a daily basis (x-axis)

*Note:*
- The history graph may be best viewed in landscape mode (rotate your phone)
- A minimum of two recorded days is required before a graph is rendered

## Pro Features
<!-- Anchor target -->
<a id="pro-features"></a>

The following features may require an upgrade to the Pro tier.

- Edit past days
- Export data (to CSV format)
- Import data

## How to View or Edit Past Days ##

- Tap the **Today** button and pick a past day to view
- To edit a past day, first view it as above then tap the **pencil** icon

## How to Export ##

Use Export to backup your historical data. For privacy reasons, data is not stored on servers. 

Why back up? In the situation where you change phones or you accidently clear the app data via Android settings, the history will be erased. 

For best practice, periodically using Export to back up.

Tapping **Export** will prompt to share a CSV (comma separated values) file with other apps on your phone. 

Share with the Google Drive app to save history in your private Google account on Google servers.

Alternatively, you may wish to share to an email app (e.g. Gmail) and send the CSV file as an attachment.

Steps to Export historical data to Google Drive:
- Tap the **Export** button
- Select the Google Drive app
- Tap **Upload** to save CSV data file to the Google server

Steps to Export historical data to Gmail:
- Tap the **Export** button
- Select the Gmail app and notice email subject and attachment CSV file
- Enter a "To" value and touch Send to forward the data to a target email address (e.g. yourself)


*Advanced Usage:*

The exported CSV file can also be used to load into a spreadsheet program such as Google Sheets or Microsoft Excel. This will allow you to integrate with other data and/or build more complex charts and graphs.

The format of the contents of the CSV text file is simple:

date,count<br>
YYYY-MM-DD,nn<br>
YYYY-MM-DD,nn<br>
...

The first line of the CSV file are headers "date,count" and each line afterwards will represent the event count for a given date.

For example, a CSV file with entries like this ...

date,count<br>
2026-01-01,5<br>
2026-01-03,17<br>

... will import two dates (January 1, 2026 and January 3, 2026) of historical data into the app.

## How to Import ##

Use Import to recover previously backed up event counts or to load historical daily event counts from another source. 

The format of the file expected by Import is the same as described above for Export. Be sure to include the header line exactly as above and dates that are in the past (not future).

## FAQ

**What's the difference between resetting the counter for the day and clearing the counter for the day?**

In the case of a reset, the counter goes to zero. Zero health events for the day may be meaningful. In the case of clear, there is no data recorded for that day (until you tap the **+**). For history (trending) it may be important to distinguish between days you have had zero events verus days that you decided not to record anything.


