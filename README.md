# CropGuard AI (prototype)
Requires Node 18+.
```
npm install
npm run dev      # http://localhost:5173
npm run build    # type-check + production build
```
Predictions are SIMULATED (`src/lib/predict.ts`). To plug in a real model, implement `predictWithModel` and set `export const predict = predictWithModel`.
Disease info lives in `src/data/diseases.ts`. History is stored in localStorage.
