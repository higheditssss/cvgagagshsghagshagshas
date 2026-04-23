# kick chat overlay

Chat overlay Kick.com cu OAuth oficial, 7TV, 9 animații.

## setup OAuth

1. **https://kick.com/settings/developer** → Create App
2. Redirect URI: linkul tău Vercel (ex: `https://pola.vercel.app`)
3. Scopes: `user:read channel:read events:subscribe chat:write`
4. copiezi Client ID + Client Secret
5. în overlay → ⚙ → paste → Login cu Kick

## utilizare

- deschizi linkul Vercel
- scrii canalul → connect
- ⚙ → animație + copy link OBS

## OBS

Browser Source → URL → 420×720

## parametri URL

- `?overlay=1` — ascunde UI
- `?channel=highman` — canal
- `?anim=slide-left` — animația
