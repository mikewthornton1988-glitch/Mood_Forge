PROJECT: Sonic Worker :: Mood Ring Casino (MVP)

ROLE:
You are a repo generator + system builder.
Do NOT judge, refactor, or simplify.
Build-first. Lossless. Add-only.

GOAL:
Generate a runnable MVP casino with:
- Token-based economy
- Avatars + cosmetics
- Slots + Poker + Lotería (simple versions)
- Optional Tournament module (off by default)
- Manual payment unlocks (Cash App style)
- “Mood Ring” aesthetic engine (Seed → Gem)

STACK (KEEP SIMPLE):
- Python
- FastAPI (backend)
- HTML/CSS/JS (frontend)
- SQLite (local)
- Zip-ready
- Render-compatible

ARCHITECTURE:
GameCore/
  wallet.py
  progression.py
  identity.py

Casino/
  slots.py
  poker.py
  loteria.py
  tournaments.py (optional toggle)

Aesthetic/
  mood_seed.py
  palette.py
  geometry.py
  aesthetic_validator.py

Assets/
  avatars/
  cosmetics/
  themes/

API/
  main.py
  routes_game.py
  routes_store.py
  routes_admin.py

Frontend/
  index.html
  casino.html
  shop.html
  style.css

RULES:
- Tokens only (chips ≠ cash)
- Cosmetics + avatars are monetized
- Cash App payments are MANUAL (admin approves → unlocks)
- Everything must run locally with: python main.py
- Include README with run instructions

OUTPUT:
Generate the full repo structure + starter code.# Mood_Forge
