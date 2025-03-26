# Website Healthcheck Status

This repository automatically checks the status of configured websites every 30 minutes using GitHub Actions.

## Last Website Status Check

*The latest health check results will be updated here by the workflow.*

⏱️ **This report is automatically refreshed every 30 minutes.**

---

### ✅ How It Works
- The workflow pings each website and records its status (UP or DOWN).
- Updates this `README.md` with the most recent check results.
- Creates a detailed timestamped report under the `Healthcheck Reports/` folder.
- The automated check runs every 30 minutes without manual intervention.

---

## Healthcheck Reports Archive
You can find historical reports inside the `Healthcheck Reports/` folder, with filenames in the format:
```
report-DDMMYYYY-HH-MM.md
```

Each report contains the detailed results of that specific check.

---

## Websites Monitored
- https://thenocturnaldevgyspy.vercel.app
- https://beacons.ai/thenocturnaldevgyspsy

*More websites can be added easily in future updates.*
