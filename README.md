# Bold Administraties

Website voor Bold Administraties.

## Cloudflare Pages
Koppel deze repo aan Cloudflare Pages voor automatische deploys.

1. Ga naar Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
2. Selecteer deze repo.
3. Build command: leeg laten (statische site).
4. Output directory: `/` of leeg.
5. Voeg custom domain `boldadministraties.nl` toe.

Nieuwe blogposts: push een update naar `blog.html` of voeg nieuwe HTML-bestanden toe. Cloudflare publiceert automatisch.