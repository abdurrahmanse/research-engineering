# 10 — Edge Auth (Passkeys + WebAuthn)

Passwordless authentication using passkeys — the 2026 default for new apps.

## Files

- `01_webauthn_ceremony.ts` — Registration + assertion ceremony, base64url encoding
- `02_session_token.ts` — Signed, short-lived session tokens stored in HttpOnly cookies
- `03_auth_middleware.ts` — Edge middleware that validates sessions on every request

## Stack

TypeScript · WebAuthn · Edge middleware · JWT / signed cookies
