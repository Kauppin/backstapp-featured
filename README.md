# backstapp-featured

Backstapp-sovelluksen aulan Ajankohtaista-osion (FEATURED) julkaistut tiedostot, jotka GitHub Pages
tarjoilee osoitteesta https://featured.backstapp.com.

- `v1/featured.json`: tuotanto. `v1/featured-staging.json`: testikanava, jota lukevat vain dev-buildit.
- `v1/img/`: kuvat, jotka on nimetty sisältönsä SHA-256-tiivisteen mukaan.

Tiedostot on allekirjoitettu Ed25519-avaimella, joka ei ole GitHubissa. Sovellus hylkää kaiken, mitä ei
ole allekirjoitettu, joten tiedostoja ei muokata käsin. Ne tehdään sovellusrepon työkalulla
`mobile/scripts/featured/featured.sh sign` (ohje: `design/featured/README.md`).
