# Webinar – Assist 0.7.0

Opptak og presentasjon fra release-webinaret for Assist 0.7.0 (oktober 2026).

| Fil | Innhold |
| --- | --- |
| `assist-webinar-0.7.0.mp4` | Opptak av webinaret, trimmet til selve gjennomgangen (Git LFS) |
| `Assist-0.7.0-Dette-faar-du-se.pptx` | Presentasjonen som ble vist: agenda, én side per demo, «Andre nyheter» |
| `index.html` | Visningsside med videospiller |

▶ **[Se webinaret](https://lrudlang-cloud.github.io/Assist-videos/webinar-0.7.0/)**

## Innhold i webinaret

1. Tjenestemaler – stasjonen bestemmer standarden
2. Meldingsmaler – SMS og e-post fra Assist
3. Ny sjåførapp – guidet flyt fra oppdrag til Kvittert
4. Avtaleprodukter og fakturering
5. Dispatch og kontoroversikt
6. Andre nyheter i 0.7.0

Assist Central og Call Assist dekkes i eget webinar.

## Legge inn videoen

Videofilen lagres med [Git LFS](https://git-lfs.com) fordi den er større enn GitHubs grense på 100 MB per fil.

```bash
git lfs install
cp /sti/til/opptaket.mp4 webinar-0.7.0/assist-webinar-0.7.0.mp4
git add webinar-0.7.0/assist-webinar-0.7.0.mp4
git commit -m "Legg til opptak av webinar 0.7.0"
git push
```

Merk: GitHub Pages serverer ikke LFS-filer, så videospilleren på visningssiden virker bare hvis filen er under 100 MB og lagres som vanlig fil (fjern da `webinar-0.7.0/*.mp4` fra `.gitattributes`), eller hvis `<source>` i `index.html` peker til en ekstern lenke (OneDrive/Stream eller YouTube).
