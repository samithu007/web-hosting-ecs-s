# MediFlow — GitHub Pages

This package is a static, localStorage/sessionStorage demo of the MediFlow e-channeling system.

## GitHub Pages deployment
1. Create a GitHub repository.
2. Upload everything in this folder to the repository root (do not upload the outer ZIP folder itself).
3. Commit and push to the `main` branch.
4. Open GitHub → Settings → Pages.
5. Under Build and deployment, choose **Deploy from a branch**.
6. Select `main` and `/ (root)`, then Save.
7. Open the generated GitHub Pages URL.

## Demo accounts
- Admin: `admin / Admin@123`
- Doctor: `dr.nimal / Doctor@123`
- Patient: `patient / Patient@123`

## Important
- This is a frontend demo. Data is stored in the browser using localStorage/sessionStorage.
- Card payments are validation/demo flows; no real card is charged.
- Real authentication, database persistence, secure payment processing and server-side authorization require a backend.
