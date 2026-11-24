# dataremoval-flows

Signed updates of the site instructions ("flows") used by the DataRemoval app.

- `flows.signed.json`: the current bundle. It is signed with an Ed25519 key that is kept
  offline, and the app checks the signature and every flow before using it.
- The files hold site instructions only. No personal data.
