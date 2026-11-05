# YEL 2026 -konseptiprototyyppi (Elo)

Luottamuksellinen konseptiprototyyppi. Avautuu salasanalla.

## Julkaisu GitHub Pagesiin
1. Luo uusi repositorio (suositus: yksityinen, jos tilisi sallii Pagesin yksityisille repoille).
2. Lisää tämän kansion `index.html` repositorion juureen.
3. Settings → Pages → Source: *Deploy from a branch* → `main` / `root` → Save.
4. Osoite näkyy samalla sivulla muutaman minuutin kuluttua.

## Tietoturva
- Prototyypin sisältö on salattu (AES-256-GCM, avain johdetaan salasanasta PBKDF2:lla). Ilman salasanaa sisältöä ei voi lukea sivun lähdekoodista. Suojaus on yhtä vahva kuin salasana: lyhyt tai arvattava salasana pysäyttää satunnaiset katsojat, mutta ei määrätietoista arvaajaa.
- Kirjautumissivun taustakuva ei ole salattu.
- Sivu pyytää hakukoneita olemaan indeksoimatta sitä (`noindex`).
- Salasana muistetaan vain saman selainvälilehden ajan.
- Älä lisää repositorioon salaamatonta lähdetiedostoa.

## Käyttö
- Sisäinen arviointinäkymä (huomiot, merkinnät, näkymälista): lisää osoitteen perään `#review`.
- Tunnistautuminen on simuloitu, eikä prototyyppi tallenna eikä lähetä mitään tietoja.
