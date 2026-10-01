# Trade Avata

Complete static GitHub Pages package for the Trade Avata product.

## Deploy
1. Upload every file/folder in this package to the root of the your GitHub repository.
2. Keep `index.html` at the repository root.
3. In GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
4. Save and open the generated Pages URL.

This version intentionally uses no build system, so there is no npm/lockfile/build-step failure.

## Backend
The UI is prepared for Firebase Authentication/Firestore/Storage and secure broker integrations, but credentials and real broker connections are NOT embedded. Demo data is clearly used where live data is unavailable.

## Production checklist
- Connect Firebase Auth/Firestore/Storage.
- Add server-side broker/account integrations.
- Replace demo indicator/catalog data with admin-managed data.
- Connect PDF/XLSX report generation.
- Replace placeholder legal copy with reviewed legal documents.
