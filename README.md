# Better Samal

A community-run portal for **Samal, Bataan**: municipal officials, offices, services and public information in one place.

Better Samal is a volunteer project listed in the [BetterGov.ph LGU Directory](https://lgu.bettergov.ph/). It is **not** an official website of the Municipality of Samal.

## About Samal

Samal is a coastal municipality on the eastern side of Bataan province in Central Luzon, bordered by Orani to the north, Abucay to the south, and Manila Bay to the east. It has 14 barangays and is known for araro, a biscuit made from arrowroot flour, as well as fishponds and aquaculture along the bay.

| Barangay | Population (2020) |
|---|---|
| East Calaguiman | 2,789 |
| East Daang Bago | 1,314 |
| Gugo | 3,639 |
| Ibaba | 3,230 |
| Imelda | 3,058 |
| Lalawigan | 4,787 |
| Palili | 2,284 |
| San Juan | 4,456 |
| San Roque | 936 |
| Santa Lucia | 2,555 |
| Sapa | 4,638 |
| Tabing Ilog | 2,289 |
| West Calaguiman | 1,534 |
| West Daang Bago | 793 |

Sources: [PhilAtlas (PSA data)](https://www.philatlas.com/luzon/r03/bataan/samal.html), [Provincial Government of Bataan](https://bataan.gov.ph/samal/).

## Run it locally

Requires Node.js 18 or newer.

```bash
npm install
npm run dev
```

Then open http://localhost:5173.

Site content lives in `content/` (Markdown and YAML) and `src/data/`. See [CONTENT-MANAGEMENT.md](CONTENT-MANAGEMENT.md) for how to edit pages without touching code.

## Contributing

Many service pages are still placeholders. If you know how a service works in Samal (requirements, office, fees, schedule), open an issue or a pull request. Please cite a public source for facts about officials, offices and fees.

## Credits

Built on the [Better Local Gov](https://github.com/iyanski/betterlocalgov) starter kit by the BetterGov.ph community. Released under [CC0 1.0](LICENSE).
