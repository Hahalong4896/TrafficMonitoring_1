# Singapore Checkpoint Traffic Monitor

Automated traffic monitoring for Singapore checkpoints (Tuas & Woodlands).

## Latest Capture
- **Last Updated**: 2026-05-29T06:49:57.582371+08:00
- **Total Days Monitored**: 49
- **Total Captures**: 1416

## Recent Captures

- **2026-05-29**: 7 capture(s), 28 image(s)
- **2026-05-28**: 30 capture(s), 120 image(s)
- **2026-05-27**: 25 capture(s), 100 image(s)
- **2026-05-26**: 21 capture(s), 84 image(s)
- **2026-05-25**: 30 capture(s), 120 image(s)
- **2026-05-24**: 30 capture(s), 120 image(s)
- **2026-05-23**: 28 capture(s), 112 image(s)


## Camera Locations

This project monitors the following checkpoint cameras:

### Tuas Checkpoint
- Camera 4703: Tuas Second Link
- Camera 4713: Tuas Checkpoint
- Camera 4714: AYE (Tuas) - Near West Coast Walk

### Woodlands Checkpoint
- Camera 2701: Woodlands Causeway (Towards Johor)
- Camera 2702: Woodlands Checkpoint

## Data Structure

```
traffic_images/
├── YYYY-MM-DD/
│   ├── camera_XXXX_YYYY-MM-DD_HH-MM-SS.jpg
│   ├── metadata_YYYY-MM-DD_HH-MM-SS.json
│   └── ...
└── summary.json
```

## Filename Format

Files are named with both date and time (Singapore timezone):
- `camera_4703_2026-01-23_05-30-45.jpg`
  - Camera ID: 4703
  - Date: 2026-01-23
  - Time: 05:30:45 SGT

## Image Analysis

To analyze traffic patterns:
1. Browse to specific date folders
2. Compare images across different days at the same time
3. Compare Tuas vs Woodlands checkpoint traffic
4. Check metadata files for camera details and timestamps

## How to Use

1. View images directly in GitHub by navigating to date folders
2. Download entire repository to analyze locally
3. Use metadata JSON files to correlate images with exact timestamps

---

*Automated by GitHub Actions - Captures at multiple times daily (Singapore Time)*
