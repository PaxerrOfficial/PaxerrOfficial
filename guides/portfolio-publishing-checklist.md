# Portfolio publishing checklist

A reusable handoff checklist for turning original design recordings into clearly documented portfolio posts.

This is based on Paxerr's [four-project timelapse workflow](https://www.linkedin.com/pulse/how-we-adapted-four-design-timelapses-landscape-portrait-feeds-rzn2e/), first published on October 16, 2026. It is a process template, not a promise of audience growth or a list of current platform upload limits.

## 1. Preserve the source

- [ ] Confirm permission to publish the project, artwork and any client identifiers.
- [ ] Keep the original recording unchanged.
- [ ] Record its filename and SHA-256 hash.
- [ ] Export derivatives into a separate folder.
- [ ] Record what the team actually contributed and the approved case-study URL.

A hash helps identify a file. It does not prove ownership or permission.

## 2. Choose the framing

- [ ] Choose the canvas for the intended placement.
- [ ] Start by fitting the full composition inside it without stretching.
- [ ] Check whether the work is legible at the size people will see in a feed.
- [ ] If an interaction is too small, make a separate close-up rather than silently cropping away essential context.
- [ ] Keep project titles away from the placement's interface overlays.

For our documented batch, we exported 1920 × 1080 landscape and 1080 × 1350 portrait versions. Those were editorial choices for that batch, not universal platform requirements.

## 3. Review the complete export

- [ ] Check dimensions, duration, audio and file size.
- [ ] Inspect the beginning, middle and end.
- [ ] Review intro cards, overlays and final frames for private or prohibited contact information.
- [ ] Verify that captions describe the work without inventing sales, conversion or revenue results.
- [ ] Check the destination's current rules and upload preview before submitting.
- [ ] Keep a separate derivative if a destination needs different artwork or copy.

A timelapse shows work taking shape. Commercial outcomes need their own evidence.

## 4. Keep a small manifest

Replace the example values below. Leave a field empty until it has been checked; do not copy these values into a production record as facts.

```json
{
  "project": "Example project",
  "source": {
    "file": "originals/example.webm",
    "sha256": ""
  },
  "caseStudyUrl": "",
  "exports": [
    {
      "file": "exports/example-landscape.mp4",
      "width": 1920,
      "height": 1080,
      "sha256": "",
      "reviewed": false
    },
    {
      "file": "exports/example-portrait.mp4",
      "width": 1080,
      "height": 1350,
      "sha256": "",
      "reviewed": false
    }
  ]
}
```

Keep passwords, API keys, session links and private client files out of the manifest and public repository.

## 5. Track publication separately

Use one record per account and destination:

| Field | What to record |
| --- | --- |
| Account | Exact account or Page used |
| Export | Reviewed derivative filename |
| Copy | Approved caption and relevant links |
| Schedule | Date, time and explicit time zone |
| State | Prepared, draft, scheduled, under review, public, failed or removed |
| Evidence | Confirmation or screenshot and the time checked |
| Public URL | The verified public post URL, when available |
| Follow-up | Next check or a specific blocker |

An upload is not a public post. A schedule is not delivery. Verify the resulting state, and retain failures instead of overwriting them with an assumption of success.

## 6. Review the batch

- [ ] Confirm that each public URL opens the intended project on the intended account.
- [ ] Keep scheduled and review-pending posts separate from public posts.
- [ ] Record actual viewing and enquiry data when available.
- [ ] Use that evidence to decide which format or explanation to improve next.

Underlying work: [CatProxies](https://paxerr.com/case-studies/catproxies), [Crypthost](https://paxerr.com/case-studies/crypthost), [Passle](https://paxerr.com/case-studies/passle) and [LeaksHub](https://paxerr.com/case-studies/leakshub).
