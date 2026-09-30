# SuperNav Assets

Video assets for **SuperNav: An Agentic Navigation System for Any Task in Any Scene**.

This repository contains published video assets for the SuperNav project page. It includes the existing twelve project-page videos (ten gallery videos and two overview videos), four earlier 4:3 edits retained for reproducibility, and twelve additional 1080p navigation demos with decision overlays. The webpage, images, fonts, original source footage, and local preview files are maintained separately.

The existing four `*-16x9.mp4` simulation videos preserve the complete approved picture with white side bars. The additional `*-decisions-16x9.mp4` videos use a 1920×1080 layout with a third-person robot replay, the recorded first-person view and selected point, decision bubbles, and thought cards. All files are copied from their finished edits without recompression.

## Video URLs

Use this base URL followed by a file path from the table below:

```text
https://raw.githubusercontent.com/The0xKa1/SuperNav-assets/main/
```

For reproducible links, replace `main` with the commit SHA of the desired revision.

## Navigation demos with decision overlays

These twelve additional videos cover four episodes each of Single-object Navigation, Multi-object Navigation, and Demand-driven Navigation. Each edit preserves all saved navigation movement frames in order, with reading holds added for cards. Replay rates are 10 fps for the Gaussian-splat scenes and 8 fps for AI2-THOR; edited duration is not evaluation runtime.

`AGENT NOTE` and `AGENT DESCRIPTION` cards quote publicly recorded text or tool arguments. `ACTION SUMMARY` cards summarize the actual recorded tool call where no public narration was saved. Selected-point overlays appear on the original image used for that decision. The completed episodes retain their recorded STOP actions.

| Task | File | Duration (s) | Size (MiB) |
| --- | --- | ---: | ---: |
| Single-object Navigation | `assets/videos/gallery/sim-single-laptop-decisions-16x9.mp4` | 70.700 | 7.27 |
| Single-object Navigation | `assets/videos/gallery/sim-single-bathtub-decisions-16x9.mp4` | 132.300 | 22.01 |
| Single-object Navigation | `assets/videos/gallery/sim-single-pink-bed-decisions-16x9.mp4` | 82.000 | 13.16 |
| Single-object Navigation | `assets/videos/gallery/sim-single-microwave-decisions-16x9.mp4` | 54.900 | 6.88 |
| Multi-object Navigation | `assets/videos/gallery/sim-multi-cafe-decisions-16x9.mp4` | 65.600 | 12.60 |
| Multi-object Navigation | `assets/videos/gallery/sim-multi-lounge-decisions-16x9.mp4` | 94.700 | 16.35 |
| Multi-object Navigation | `assets/videos/gallery/sim-multi-livingroom-decisions-16x9.mp4` | 116.000 | 19.97 |
| Multi-object Navigation | `assets/videos/gallery/sim-multi-crossroom-decisions-16x9.mp4` | 216.200 | 27.61 |
| Demand-driven Navigation | `assets/videos/gallery/sim-demand-work-area-decisions-16x9.mp4` | 113.500 | 19.08 |
| Demand-driven Navigation | `assets/videos/gallery/sim-demand-bathroom-decisions-16x9.mp4` | 68.875 | 11.83 |
| Demand-driven Navigation | `assets/videos/gallery/sim-demand-lost-items-decisions-16x9.mp4` | 148.500 | 25.35 |
| Demand-driven Navigation | `assets/videos/gallery/sim-demand-cleaning-supplies-decisions-16x9.mp4` | 56.375 | 6.10 |

## Existing project-page videos and earlier edits

| File | Size (MiB) |
| --- | ---: |
| `assets/videos/gallery/real-find-printer-then-trashbin.mp4` | 18.19 |
| `assets/videos/gallery/real-go-to-another-dog.mp4` | 21.12 |
| `assets/videos/gallery/real-go-to-basketball.mp4` | 15.61 |
| `assets/videos/gallery/real-go-to-trash-bin.mp4` | 11.06 |
| `assets/videos/gallery/sim-demand-driven.mp4` | 9.17 |
| `assets/videos/gallery/sim-multi-crossroom-16x9.mp4` | 13.78 |
| `assets/videos/gallery/sim-multi-crossroom.mp4` | 20.72 |
| `assets/videos/gallery/sim-multi-livingroom-16x9.mp4` | 9.91 |
| `assets/videos/gallery/sim-multi-livingroom.mp4` | 14.92 |
| `assets/videos/gallery/sim-multi-lounge-16x9.mp4` | 8.01 |
| `assets/videos/gallery/sim-multi-lounge.mp4` | 12.16 |
| `assets/videos/gallery/sim-multi-object.mp4` | 10.26 |
| `assets/videos/gallery/sim-single-laptop-16x9.mp4` | 2.49 |
| `assets/videos/gallery/sim-single-laptop.mp4` | 3.80 |
| `assets/videos/overview/overview-960.mp4` | 1.87 |
| `assets/videos/overview/overview.mp4` | 6.30 |

`manifest.json` records the size and SHA-256 checksum of each video. When updating a file, update its manifest entry as well. Keep unpublished source footage and unrelated files out of this repository.
