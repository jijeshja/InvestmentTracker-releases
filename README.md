# InvestmentTracker

**A free, offline desktop app for tracking Indian Mutual Fund and Stock investments.**

Your data stays on your machine — encrypted with AES-256 in a local database. No cloud, no login, no telemetry.

## Features

- **CAS Import** — Import CAMS / KFintech Consolidated Account Statements (PDF)
- **Broker Import** — Import stock holdings from Zerodha, Groww, Angel One, ICICI Direct, HDFC Securities and more
- **Portfolio Dashboard** — Total invested, current value, returns, asset allocation with drill-down
- **Goals & Rebalancing** — Set financial goals, allocate holdings, track glide path with interactive charts
- **NAV Sync** — One-click update of MF NAVs and stock prices
- **Secure** — AES-256 encrypted local database, no data leaves your machine
- **Cross-Platform** — Windows, Linux, and macOS

## Download

Go to the [**Releases**](https://github.com/jijeshja/InvestmentTracker-releases/releases/latest) page and download the zip for your platform:

| Platform | File |
|----------|------|
| **Windows (x64)** | `InvestmentTracker-win-x64.zip` |
| **Linux (x64)** | `InvestmentTracker-linux-x64.zip` |
| **macOS (Apple Silicon)** | `InvestmentTracker-macos-arm64.zip` |

### How to Run

**Windows:** Extract the zip → run `InvestmentTracker.exe`

**Linux:**
```bash
unzip InvestmentTracker-linux-x64.zip -d InvestmentTracker
chmod +x InvestmentTracker/InvestmentTracker
./InvestmentTracker/InvestmentTracker
```

**macOS:**
```bash
unzip InvestmentTracker-macos-arm64.zip -d InvestmentTracker
chmod +x InvestmentTracker/InvestmentTracker
./InvestmentTracker/InvestmentTracker
```

## How to Get Your CAS Statement

### From CAMS
1. Visit [camsonline.com](https://www.camsonline.com) → Investor Services → Statements
2. Select Consolidated Account Statement (CAS) → Detailed
3. The PDF will be emailed — password is your PAN in UPPERCASE

### From KFintech
1. Visit [kfintech.com](https://www.kfintech.com) → Investor Services → CAS
2. Select Detailed statement → enter PAN and email
3. The PDF will be emailed — password is your PAN in UPPERCASE

## Tech Stack

.NET 8 | Avalonia UI 11.2 | LiteDB | CommunityToolkit.Mvvm | LiveCharts2 | PdfPig

## License

Free for personal use.
