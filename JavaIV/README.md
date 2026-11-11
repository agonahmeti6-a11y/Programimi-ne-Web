# Java IV — Fotografia me telefon

## Shpjegimet

- `link rel="stylesheet"` lidh dokumentin HTML me skedarin e jashtëm `style.css`, ku ruhen rregullat e pamjes.
- `margin` krijon hapësirë jashtë kufirit të elementit; `padding` krijon hapësirë brenda kufirit, mes përmbajtjes dhe skajit.
- `.faqja` përdor `max-width: 680px` që përmbajtja të mos bëhet tepër e gjerë në ekranet e mëdha, ndërsa `width: 100%` e lejon të përshtatet në ekrane të vogla.

## Rezultatet e testimit

Testet u kryen në shfletues me të dhëna të sajuara.

- Në gjerësi 360px, gjerësia e dokumentit ishte 345px; nuk pati scroll horizontal. Tri kutitë dhe fushat mbetën brenda faqes.
- Në gjerësi 1000px, përmbajtja ishte e përqendruar me gjerësi maksimale 680px; tri kutitë mbetën vertikale.
- CSS u ngarkua dhe titulli u shfaq me ngjyrën blu të kërkuar.
- Klikimi i etiketës “Emri” fokusoi fushën përkatëse; me Tab u pa treguesi i fokusit.
- Formulari bosh, emaili pa format të vlefshëm dhe përvoja e pazgjedhur nuk u pranuan.
- Me të dhëna prove të vlefshme, formulari hapi `index.html` me parametrat `emri`, `email` dhe `pervoja` në adresë. Të dhënat nuk ruhen në server.

Para dorëzimit, zëvendësoni “Emri Mbiemri” në fund të faqes me emrin e autorit.
