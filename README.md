# ATM Sentinel Portfolio

A three-page static portfolio presenting **ATM SENTINEL: ATM Transaction Anomaly Detection**, an academic prototype that explores anomaly detection using synthetic ATM transaction data.

The website uses plain HTML, CSS and a small JavaScript file. It has no backend, build step, API key or paid-service dependency, and can be hosted directly with GitHub Pages.

## Pages and files

| File | Purpose |
| --- | --- |
| `index.html` | Project overview, problem, aim, objectives, proposed solution, technologies and editable student details |
| `system.html` | Workflow diagram, technology explanations, application features and synthetic dataset information |
| `results.html` | Demonstration statistics, interpretation, limitations and verified project-resource links |
| `style.css` | Shared responsive design, components and reduced-motion support |
| `script.js` | Accessible small-screen navigation menu |

Student information on the Home page is intentionally shown as editable bracketed placeholders. Replace those values before presenting or submitting the portfolio.

## Preview locally

Open `index.html` in a modern browser. For a local web server, open PowerShell in this folder and run:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>. Stop the server with `Ctrl+C`.

## Publish with GitHub Pages

1. Open the existing portfolio repository: <https://github.com/desire1515/ATM-Sentinel-Portfolio>.
2. Select the **`main`** branch in the branch selector.
3. Select **Add file → Upload files**.
4. Upload all six files from this portfolio folder. Keep `index.html`, `system.html` and `results.html` at the repository root (do not place them in a subfolder).
5. Enter a commit message, leave **Commit directly to the `main` branch** selected, then select **Commit changes**.
6. In the repository, open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Set the branch to **`main`** and the folder to **`/ (root)`**, then select **Save**.
9. Wait for the Pages deployment to complete. Check the Pages section for its published status and URL.

Expected URL after GitHub Pages is enabled: <https://desire1515.github.io/ATM-Sentinel-Portfolio/>.

The URL is an expected address only; this repository's deployment has not been verified by this portfolio build.

## Project source and data

- Source repository: <https://github.com/desire1515/ATM-Sentinel>
- Setup instructions: <https://github.com/desire1515/ATM-Sentinel/blob/main/README.md>
- Dataset folder: <https://github.com/desire1515/ATM-Sentinel/tree/main/dataset>
- Synthetic dataset CSV: <https://github.com/desire1515/ATM-Sentinel/blob/main/dataset/atm_transactions_malawi_synthetic.csv>

The portfolio describes demonstration statistics only. Its dataset is synthetic; anomaly flags and review tiers are not evidence or probabilities of fraud. The ATM Sentinel prototype is not connected to live bank or ATM systems and makes no real-time fraud-prevention or production-deployment claim.
