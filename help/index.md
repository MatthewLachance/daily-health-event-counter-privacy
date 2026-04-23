# Help – Daily Health Event Counter App for Android

#### Quick Start ####
- Tap **<span style="font-size: 18px;">+</span>** to record a health event
- Use the **Today** (date picker) button to view or edit past days
- Tap **History** to see trends
- Each day at midnight, the event count clears after saving previous day

<details>
  <summary><strong>About this App</strong></summary>
<br>
Ideal for monitoring symptoms, habits, or medical tracking between appointments.
  
Key Features:
<ul>
  <li>One-tap event tracking throughout the day</li>
  <li>Automatic daily reset with history preserved</li>
  <li>View trends over time with built-in history line graph</li>
  <li>Review and edit past days easily</li>
  <li>Big buttons for easy over night use</li>
  <li>Export data for backup or to paste into spreadsheet</li>
  <li>Import CSV file to load the app with historical data</li>
  <li>Export then Import when changing phones</li>
  <li>Works offline — no account required</li>
  <li>No data sharing — your information stays on your device</li>
  <li>App languages: English, français</li>
</ul>

Use Cases
<ul>
  <li>Track daily symptoms (bathroom visits, pain, headache frequency, etc.)</li>
  <li>Monitor habits or recovery progress</li>
  <li>Provide accurate data to healthcare providers</li>
  <li>Or just count things (with daily history)</li>
</ul>

This app is ideal for personal tracking and for sharing accurate data with healthcare professionals when needed.

All data is saved locally on your phone.

</details>

<details>
  <summary><strong>How to Adjust Daily Counter</strong></summary>
<br>
  
- Tap **<span style="font-size: 18px;">+</span>** to add one to the counter
- Tap **<span style="font-size: 18px;">-</span>** to reduce the counter by one
- Use **Reset** to set the counter back to zero (you’ll be asked to confirm)
- Use **Clear data** to remove all entries for this day (you’ll be asked to confirm)

*Note:* 
- The counter automatically clears when a new day starts (midnight)
- Your previous day counter value is saved for use in observing trend (history).
</details>

<details>
  <summary><strong>How to View History</strong></summary>
<br>
  
- Tap the **History** button to view a trend of events over time
- The graph shows the total event values (y-axis) on a daily basis (x-axis)

*Note:*
- The history graph may be best viewed in landscape mode (rotate your phone)
- A minimum of two recorded days is required before a graph is rendered
</details>

<!-- Anchor target -->
<a id="pro-features"></a>
<details>
  <summary><strong>Pro Features</strong></summary>
<br>

The following features may require an upgrade to the Pro tier.

- Edit past days
- Export data (to CSV format)
- Import data

To upgrade, tap the "i" (information) button in the app.
</details>

<details>
  <summary><strong>How to View or Edit Past Days</strong></summary>
<br>

- Tap the **Today** button and pick a past day to view
- To edit a past day, first view it as above then tap the **pencil** icon
</details>

<details>
  <summary><strong>How to Export</strong></summary>
<br>
Use Export to backup your historical data. For privacy reasons, data is not stored on servers. 

Why back up? In the situation where you change phones or you accidently clear the app data via Android settings, the history will be lost. 

To safeguard against this, periodically use Export for backup.

Tapping **Export** will prompt to share a CSV (comma separated values) file with other apps on your phone. 

Share with the Google Drive app to save history in your private Google account on Google servers.

Alternatively, you may wish to share to an email app (e.g. Gmail) and send the CSV file as an attachment.

Steps to Export historical data to Google Drive:
- Tap the **Export** button
- Select the Google Drive app
- Tap **Upload** to save CSV data file to the Google Drive server

Steps to Export historical data to Gmail:
- Tap the **Export** button
- Select the Gmail app and notice a draft email with appropriate subject and attached CSV file
- Enter a **To** value and touch **Send** to forward the information to an email address


*Advanced Usage:*

The exported CSV file can also be used to load into a spreadsheet program such as Google Sheets or Microsoft Excel. This will allow you to integrate with other data or build more complex charts and graphs.

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
</details>

<details>
  <summary><strong>How to Import</strong></summary>
<br>
Use Import to recover previously backed up event counts or to load historical daily event counts from another source. 

The format of the file expected by Import is the same as described above for Export. Be sure to include the header line exactly as above and dates that are in the past (not future).
</details>

<details>
  <summary><strong>FAQ</strong></summary>
<br>

**What's the difference between resetting the counter for the day and clearing the counter for the day?**

A reset adjusts the counter to zero. A clearing of data removes data recorded for that day. For history (trends) it may be important to distinguish between days that have zero events and days where no events were  recorded.
</details>

