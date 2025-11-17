- **Date**  
  Calendar date for the metrics in `YYYY-MM-DD` format.

- **Views**  
  Total number of views on the channel for that date.

- **Watch time (hours)**  
  Total watch time across all videos for that date, in hours.

---

## File: Table data.csv  (video-level summary)

- **Content**  
  YouTube video ID.

- **Video title**  
  Title of the Short at the time of data export.

- **Views**  
  Lifetime view count for the video at the time of export.

- **Watch time (hours)**  
  Total lifetime watch time for this video, in hours.

- **Average view duration (seconds)**  
  Average watch time per view, in seconds.

- **Average percentage viewed (%)**  
  Average fraction of the video watched per view, expressed as a percentage.

- **Engaged views**  
  YouTube’s engaged-view count for this video (views above a minimum
  watch threshold).

- **Impressions**  
  Number of times the thumbnail/Short was shown to potential viewers.

- **Impressions click-through rate (%)**  
  Percentage of impressions that resulted in a view.

- **Row 0 note**  
  Row 0 is an aggregated “All videos” row. It should not be treated as a
  single video in analyses.

---

## File: Chart data.csv  (video × date)

- **Date**  
  Calendar date in `YYYY-MM-DD` format.

- **Content**  
  YouTube video ID.

- **Video title**  
  Title of the Short.

- **Video publish time**  
  UTC publish timestamp string as provided by YouTube.

- **Duration (sec)**  
  Video length in seconds.

- **Views**  
  Number of views for this specific video on this specific date.