# Postavljanje okoline

## Stvaranje virtualnog okruženja

- U terminalu pokrenuti naredbu `python -m venv venv` za stvaranje virtualnog okruženja
- Okruženje se pokreće naredbom `venv/Scripts/activate`

## Preuzimanje potrebnih biblioteka

- Za preuzimanje svih potrebnih biblioteka pokrenuti naredbu `pip install -r requirements.txt`

## Stvaranje varijabli okruženja

- Kreirati datoteku `.env` u kojoj se inicijaliziraju varijable `SPOTIPY_CLIENT_ID`, `SPOTIPY_CLIENT_SECRET`, `SESSION_COOKIE_NAME`, `SECRET_KEY` sa odgovarajućim vrijednostima preuzetim sa Spotify Developers dashboarda za kreiranu aplikaciju.

## Pokretanje aplikacije

- Pokrenuti python datoteku i pratiti poveznicu u terminalu. Ukoliko je uspješno pokrenuta aplikacija i podaci su točni, potrebno je prijaviti se u vlastiti Spotify račun kako bi se omogućio pristup medijateci.
