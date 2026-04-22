# 📺 TV Position Guide — 65" vs 75" Comparison

> A data-driven visual guide for optimal TV placement based on room dimensions, viewing distance, and ergonomic standards.

---

## 🗂️ Files in This Repo

| File | Description |
|---|---|
| `index.html` | Interactive visual comparison page — open in browser |
| `style.css` | All styles for the HTML page |
| `notes.txt` | Raw data, formulas, and scoring logic in plain text |
| `README.md` | This documentation |

---

## 🏠 Room Data Summary

| Parameter | Value |
|---|---|
| TV Wall Width | 146 inches (12'2") |
| Viewing Distance | 108 inches (~9 ft) |
| Room Height | 120 inches (10 ft) |
| Extra Space Behind Sofa | 9 inches (max) |
| Eye Level (Seated) | ~42–44 inches from floor |
| Ideal Viewing Zone | 66 inches wide (±33" from center) |

---

## 📐 TV Specifications

| Specification | 65" TV | 75" TV |
|---|---|---|
| Diagonal | 65 inches | 75 inches |
| Screen Width | 57.3" | 66.0" |
| Screen Height | 32.2" | 37.0" |
| Screen Area | 1,844 sq in | 2,442 sq in (+32.5%) |
| Ideal Viewing Distance | 7.0 – 8.1 ft | 8.0 – 9.4 ft |
| Your Distance (9 ft) | ⚠️ Too far | ✅ Perfect |
| TV Center from Floor | ~40.6" | 42.5" |
| TV Bottom from Floor | ~24.5" | 24.0" |

---

## 👁️ Viewing Angle Zones

Calculated at 9 ft (108") viewing distance using `X = tan(angle) × 108"`:

| Zone | Angle | 65" X Range | 75" X Range |
|---|---|---|---|
| 🟢 Perfect | 0°–17° | 0 to ±26.6" | 0 to ±33.0" |
| 🔵 Good | 17°–30° | ±26.6" to ±46.5" | ±33.0" to ±60.0" |
| 🟡 OK | 30°–40° | ±46.5" to ±62.4" | ±60.0" to ±80.0" |
| 🔴 Limit | 40°+ | Beyond ±62.4" | Beyond ±80.0" |

---

## 🧮 Scoring Logic

### 1 — Distance Match
```
Is your 9 ft distance inside the TV's ideal range?

65"  Ideal 7.0–8.1 ft  →  9 ft OUTSIDE  →  45/100
75"  Ideal 8.0–9.4 ft  →  9 ft INSIDE   →  96/100
```

### 2 — Screen Immersion (FOV)
```
FOV = 2 × arctan( screen_width / (2 × distance_inches) )
Target: ~20° for cinematic feel

65"  2 × arctan(57.3 / 216) ≈ 15.2°  →  58/100
75"  2 × arctan(66.0 / 216) ≈ 17.5°  →  90/100
```

### 3 — Eye Level Match
```
Seated eye level target: 42–44" from floor

65"  TV center ~40.6"  →  1.4–3.4" too low  →  70/100
75"  TV center  42.5"  →  spot on range      →  97/100
```

### 4 — Seating Zone Width
```
Perfect zone = tan(17°) × 108" = ±33" (guide standard)

65"  ±26.6"  →  narrower than ±33"  →  62/100
75"  ±33.0"  →  matches exactly     →  95/100
```

### 5 — Value for Money
```
65"  Lower price   →  88/100
75"  Higher price  →  75/100
```

### 6 — Overall (simple average)
```
Overall = (Score1 + Score2 + Score3 + Score4 + Score5) / 5

65"  (45 + 58 + 70 + 62 + 88) / 5 = 65/100
75"  (96 + 90 + 97 + 95 + 75) / 5 = 91/100
```

---

## 🏆 Final Verdict

| Category | 65" | 75" | Winner |
|---|---|---|---|
| Distance Match | 45/100 | 96/100 | ✅ 75" |
| Screen Immersion | 58/100 | 90/100 | ✅ 75" |
| Eye Level Match | 70/100 | 97/100 | ✅ 75" |
| Seating Zone Width | 62/100 | 95/100 | ✅ 75" |
| Value for Money | 88/100 | 75/100 | ✅ 65" |
| **Overall** | **65/100** | **91/100** | **✅ 75" WINS** |

> **Go with the 75".** Your 9 ft room is sized perfectly for it. The 65" falls outside its ideal viewing distance, scores lower on immersion, eye level, and seating zone width. The only trade-off is cost.

---

## ✅ Key Recommendations

- Keep TV center at eye level when seated (~42" from floor)
- Viewing distance of ~9 ft is ideal for a 75" TV
- Ideal seating area is within ±33" from the center
- Symmetrical seating provides the best overall experience
- Side seats (up to ±60°) are still good for general viewing
- Corner seats (beyond ±60°) will have noticeable angle loss
- Maximum extra space behind sofa: 9 inches

---

*All calculations based on room layout guide with dimensions: 146" wide wall, 108" viewing distance, 120" room height.*
