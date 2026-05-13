# Australian Tesla Registration Plates

Custom Australian state and territory registration plate images for the Tesla Paint Shop (Toybox) app.

## Plates Included

### Australian Capital Territory
| File | Style |
|------|-------|
| `act_bush_capital.png` | Blue on white — "CANBERRA – THE BUSH CAPITAL" |
| `act_standard.png` | Blue on white — "CANBERRA – THE NATION'S CAPITAL" |

### New South Wales
| File | Style |
|------|-------|
| `nsw_standard.png` | Yellow — "NEW SOUTH WALES" |
| `nsw_premium_white.png` | White/chrome — "NEW SOUTH WALES" |
| `nsw_premium_black.png` | Black — "NEW SOUTH WALES" |
| `nsw_euro_white.png` | Euro slimline white — NSW badge with state flag |
| `nsw_euro_black.png` | Euro slimline black — NSW badge with state flag |

### Northern Territory
| File | Style |
|------|-------|
| `nt_standard.png` | Orange — "N.T. OUTBACK AUSTRALIA" with Sturt's Desert Rose |

### Queensland
| File | Style |
|------|-------|
| `qld_standard.png` | Maroon on white — "QUEENSLAND / SUNSHINE STATE" |
| `qld_premium_white.png` | White — "QLD" only |
| `qld_q_plate_black.png` | Black — large Q logo, "QUEENSLAND / SUNSHINE STATE" |

### South Australia
| File | Style |
|------|-------|
| `sa_standard.png` | White — tri-colour stripe, "SOUTH AUSTRALIA" |
| `sa_rs_series_black.png` | Black — "SOUTH AUSTRALIA" |

### Tasmania
| File | Style |
|------|-------|
| `tas_standard.png` | White/blue — Thylacine emblem, "TASMANIA – Explore the possibilities" |
| `tas_heritage_black.png` | Black — "TAS / TASMANIA" |

### Victoria
| File | Style |
|------|-------|
| `vic_standard.png` | White/blue — "Victoria – The Education State" |
| `vic_future_general_issue.png` | White/blue — "VIC" only |
| `vic_heritage_black.png` | Black — "VIC / VICTORIA" |
| `vic_slimline_black.png` | Black — "VIC" only, slimline |

### Western Australia
| File | Style |
|------|-------|
| `wa_standard.png` | Blue header — WA state badge, "WESTERN AUSTRALIA" |
| `wa_optional_white.png` | White — "WA" |
| `wa_optional_black.png` | Black — "WA" |

---

## How to Load onto Your Tesla

### Step 1 — Prepare a USB drive

Format a USB drive as **FAT32** or **exFAT**, then create the following folder structure:

```
USB drive root
└── LicensePlates/
    ├── act_bush_capital.png
    ├── act_standard.png
    ├── nsw_standard.png
    ├── nsw_premium_white.png
    ├── nsw_premium_black.png
    ├── nsw_euro_white.png
    ├── nsw_euro_black.png
    ├── nt_standard.png
    ├── qld_standard.png
    ├── qld_premium_white.png
    ├── qld_q_plate_black.png
    ├── sa_standard.png
    ├── sa_rs_series_black.png
    ├── tas_standard.png
    ├── tas_heritage_black.png
    ├── vic_standard.png
    ├── vic_future_general_issue.png
    ├── vic_heritage_black.png
    ├── vic_slimline_black.png
    ├── wa_standard.png
    ├── wa_optional_white.png
    └── wa_optional_black.png
```

> The folder **must** be named `LicensePlates` (capital L and P, no spaces).

### Step 2 — Copy the images

Copy all `.png` files from the `LicensePlates/` folder in this repo into the `LicensePlates/` folder on your USB drive.

### Step 3 — Load in the car

1. Insert the USB drive into one of the front USB-A ports (or the USB hub in the centre console on newer models).
2. On the touchscreen, go to **Toybox** → **Paint Shop** (the spray can icon).
3. Tap the **license plate** area on the car model.
4. Your custom plates will appear alongside the built-in options — tap one to apply it.

### Notes

- Changes are cosmetic only and apply to the on-screen car model in Paint Shop.
- The USB drive can remain inserted or be removed after loading — plates are stored in the car.
- If your plates do not appear, confirm the folder name is exactly `LicensePlates` and that the files are PNG format.
- Tested on Tesla software version 2024.x and later. Behaviour may vary on older firmware.

## Image Specifications

| Property | Value |
|----------|-------|
| Format | PNG (transparent background) |
| Dimensions | 420 × 200 px |

## Contributing

Missing a plate style? Open a pull request with a PNG at 420×200px using the naming convention `{state}_{style}.png`.
