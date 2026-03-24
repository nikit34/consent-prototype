# Neuroom Consent Prototype

Standalone prototype for the student consent flow with:

- `Отправить ссылку родителю` as a one-tap action
- explicit `grace period`
- student pages with `pending / expired / confirmed` states
- separate parent confirmation screen
- local state machine for fast scenario testing

## Run

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Notes

- Prototype state is stored in `localStorage`.
- No backend is required.
- The share-link uses a mocked URL based on the existing Neuroom token flow.
