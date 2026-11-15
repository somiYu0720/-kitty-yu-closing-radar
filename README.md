# KITTY YU CLOSING RADAR V1.0

Private, standalone CSV-based closing radar prototype. No integration with NASDAQ 7.0. No live market feed, SEC auto-check, or scheduled scans yet.

Open index.html locally in a browser. Upload a CSV with columns ticker,price,change_pct,volume,avg_volume,low,high,close,news_score,sec_risk. Candidates are scored by heuristic RVOL, price position, news score, and volume. Scores are not predicted returns.

Save candidates in browser localStorage, then upload next-day results CSV with ticker,next_high,next_close to compare returns. No trade execution.

Security: repository is private, but GitHub Pages does not provide private website access control for personal accounts. Do not enable public Pages for this project. Browser localStorage is not encrypted; avoid sensitive credentials or secrets.
