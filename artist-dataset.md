# The Artist Dataset
## Stretch Records roster, Course 06 onward

Five artists, each with five songs and durations. This file mirrors the upstream source of truth (CLAUDE-DESIGN-HANDOFF-upstream.md, from the design sessions); type names and numbers exactly as written. Totals are the hand-added sum of the five durations, verified. This dataset carries into Course 07, where it becomes the data the learners' JavaScript works on.

House note: the duo's official name is written with an ampersand; in all course content it is written "Miyagi and Andy Panda" per the house ampersand rule. Filenames use lowercase-and-hyphens per course convention. The Celentano titles carry lang="it" in markup.

---

## Pinkfong. Children's music. 5 songs, 11:31 total
Photo `images/pinkfong.jpeg` (also every song cover).
Blurb: "The children's music powerhouse behind the most-watched video on the internet. Short, loud, unbelievably sticky."

| # | Song | Duration |
|---|---|---|
| 1 | Baby Shark | 2:16 |
| 2 | Wheels on the Bus | 2:35 |
| 3 | Five Little Monkeys | 2:05 |
| 4 | Monkey Banana | 2:24 |
| 5 | Shark Family | 2:11 |

## Adriano Celentano. Italian pop. 5 songs, 20:52 total
Photo `images/adriano-celentano.jpg` (also every song cover). Titles carry lang="it".
Blurb: "Sixty years of Italian pop in one voice: rock and roll imported, rewritten and sung back louder."

| # | Song | Duration |
|---|---|---|
| 1 | Azzurro | 3:41 |
| 2 | L'emozione non ha voce | 4:13 |
| 3 | Il ragazzo della via Gluck | 4:16 |
| 4 | Susanna | 4:26 |
| 5 | Confessa | 4:16 |

## Asake. Afrobeats. 5 songs, 14:08 total
Photo `images/asake.jpg`. Dedicated covers per song.
Blurb: "Amapiano log drums, fuji chants and street-Yoruba hooks. The loudest new voice out of Lagos."

| # | Song | Duration | Cover |
|---|---|---|---|
| 1 | Sungba | 2:47 | `images/asake-ololade.jpg` |
| 2 | Joha | 2:35 | `images/asake-mr-money-with-the-vibe.jpg` |
| 3 | Jogodo | 3:08 | `images/asake-real.jpg` |
| 4 | Amapiano | 3:22 | `images/asake-work-of-art.jpg` |
| 5 | Lonely At The Top | 2:16 | `images/asake-work-of-art.jpg` (shared) |

## Miyagi and Andy Panda. Hip-hop. 5 songs, 16:21 total
Photo `images/miyagi-and-andy-panda.jpg`. Dedicated covers per song.
Blurb: "Two rappers from Vladikavkaz, half sung and half spoken, built on dub basslines and long reverbs."

| # | Song | Duration | Cover |
|---|---|---|---|
| 1 | Kosandra | 3:18 | `images/miyagi-kosandra.jpg` |
| 2 | Utopia | 3:00 | `images/miyagi-yamakasi.jpg` |
| 3 | Minor | 3:13 | `images/miyagi-yamakasi.jpg` (shared, same album) |
| 4 | Saloon | 2:46 | `images/miyagi-saloon.jpg` |
| 5 | I Got Love | 4:04 | `images/miyagi-i-got-love.jpg` |

## Johnny Cash. Country. 5 songs, 15:40 total
Photo `images/johnny-cash.jpg` (also every song cover).
Blurb: "The man in black. Three chords, the truth, and a baritone that outlasted every genre it was filed under."

| # | Song | Duration |
|---|---|---|
| 1 | Hurt | 3:36 |
| 2 | Ring of Fire | 2:38 |
| 3 | Highwayman | 3:03 |
| 4 | God's Gonna Cut You Down | 2:38 |
| 5 | Ghost Riders in the Sky | 3:45 |

---

Production notes:
- Images ship compressed: max 800px on the long edge, JPEG quality around 60. Kilobytes, not megabytes.
- The typeface across the site is Inter from Google Fonts, the only font loaded.
- Durations are mm:ss; the totals become Course 07's first computation targets.
