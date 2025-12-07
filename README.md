# Product Business Case Calculator

A comprehensive financial modeling tool for software and hardware product managers.

## Features

- ✅ Complete cost structure modeling
- ✅ Market sizing (TAM/SAM/SOM)
- ✅ 5-year revenue projections
- ✅ Break-even analysis
- ✅ Margin analysis
- ✅ Scenario planning (Conservative/Base/Aggressive)
- ✅ Competitive pricing comparison
- ✅ Visual charts and graphs
- ✅ Export data to JSON

## Local Development

1. Clone the repository
2. Install dependencies:
```bash
   npm install
```
3. Run development server:
```bash
   npm run dev
```
4. Open http://localhost:5173

## Deployment

This project is optimized for Vercel deployment.

### Deploy to Vercel

1. Push your code to GitHub
2. Import the project in Vercel
3. Vercel will auto-detect Vite and deploy

Or use Vercel CLI:
```bash
npm install -g vercel
vercel
```

## Usage

1. Select product type (Software/Hardware)
2. Enter cost structure
3. Define market size and adoption rates
4. Set target pricing
5. Choose scenario (Conservative/Base/Aggressive)
6. Analyze results across 4 tabs:
   - **Inputs**: All assumptions and parameters
   - **Analysis**: Key metrics and financial breakdown
   - **Projections**: Visual charts and trends
   - **Sensitivity**: Scenario comparisons

## Tech Stack

- React 18
- Vite
- Recharts (for visualizations)
- Tailwind CSS
- Lucide React (icons)
