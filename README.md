# AgriVision — Vercel-ready Flask deployment

This version uses Vercel's current zero-configuration Flask deployment.

## Files
- `app.py` — Flask backend + frontend serving
- `index.html`, `style.css`, `script.js` — frontend
- `plant_disease_model.keras` — AI model
- `disease_info.json` — disease information
- `requirements.txt` — Python dependencies

## Deploy
1. Replace the files in your GitHub repository with these files.
2. In Vercel, import the repository.
3. Keep Root Directory as `./`.
4. Select **Flask** as Application Preset.
5. Deploy.

The frontend calls `/api/predict`, so no separate backend URL is required.
