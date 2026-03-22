# Hitster · Klasična glazba — Player

Web app za reproduciju Spotify trackova bez prikaza metapodataka.

## Postavljanje na GitHub Pages

1. Na GitHubu napravi novi repozitorij pod imenom: `hitster`
2. Uploadaj sve fileove iz ove mape (index.html i callback/index.html)
3. Idi na Settings → Pages → Source: `main` branch → `/root`
4. Za par minuta app je živa na: `https://zalac777.github.io/hitster/`

## Korištenje

Svaki QR kod na kartici vodi na:
```
https://zalac777.github.io/hitster/?t=SPOTIFY_TRACK_ID
```

Npr. Arvo Pärt – Spiegel im Spiegel:
```
https://zalac777.github.io/hitster/?t=2PI6xlYCPb23CZg66oe2vk
```

## Napomene

- Zahtijeva Spotify Premium za Web Playback SDK
- Spotify Free → fallback na embed player
- Token se čuva u sessionStorage (traje do zatvaranja browsera)
