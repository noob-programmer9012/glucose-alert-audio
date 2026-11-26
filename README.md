# Glucose alert audio

Recordings played by the Glucose Reader app's alert calls (through Plivo).
Each `.xml` file is the call script Plivo fetches when a call is answered; it plays the matching `.mp3` three times.

| File | When |
|---|---|
| `low.xml` | Glucose below the low limit |
| `high.xml` | Glucose above the high limit |
| `no-data.xml` | No readings for a while |
| `test.xml` | Test calls |

Generated with `scripts/make-recordings.sh` in the app's repo.
