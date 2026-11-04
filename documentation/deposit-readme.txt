╔══════════════════════════════════════════════════════════════╗
║     Thinking Behind the Mask                                   ║
║     Complete Analysis Archive                                  ║
╚══════════════════════════════════════════════════════════════╝

Author: Abbas Hamidavi
Date:   2026-07-28
Generated: 2026-07-28 20:15:45

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📁 ARCHIVE STRUCTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

mask_analysis_report/
│
├── README.txt                    — This file
├── final_report.html             — Interactive HTML report (open in browser)
├── final_summary.json            — Machine-readable complete summary
│
├── data/                         — All analysis data (CSV format)
│   ├── all_features.csv          — 141 features × 75 responses
│   ├── metacognitive_depth.csv   — Section 6 scores per response
│   ├── cluster_assignments.csv   — K-Means + Hierarchical labels
│   ├── resistance_acceptance.csv — Section 8 resistance/acceptance
│   ├── statistical_results.csv   — Section 9 test results
│   └── embeddings_umap.csv       — UMAP 2D/3D coordinates
│
├── figures/                      — All visualizations (PNG, 150+ DPI)
│   ├── section10_umap_by_model.png
│   ├── section10_umap_by_round.png
│   ├── section10_umap_kmeans_k3.png
│   ├── section10_umap_kmeans_k5.png
│   ├── section10_silhouette_analysis.png
│   ├── section10_dendrogram.png
│   ├── section10_cluster_composition.png
│   ├── section11_governance_heatmap.png
│   ├── section11_persona_radar.png
│   ├── section11_bubble_chart.png
│   ├── section11_forest_plot.png
│   ├── section11_emergence_timeline.png
│   ├── section11_correlation_heatmap.png
│   ├── section11_model_dashboard.png
│   └── section11_resistance_acceptance.png
│
└── metadata/                     — Configuration & analysis metadata
    ├── analysis_config.json
    ├── section2_parsing_report.json
    ├── section3_classification_summary.json
    ├── section4_feature_list.json
    ├── section5_metadata.json
    └── section9_statistical_report.json

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📊 QUICK STATISTICS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

• Models Analyzed:       3 (GPT-5.4, Claude 4.6, Gemini 3.1 Pro)
• Total Prompts:         75 (25 per model)
• Prompting Frames:      5 (Narrative, Engineering, Coaching, Ethnography, Philosophy)
• Features Extracted:    141
• Metacognitive Concepts: 16
• Governance Items:      199+
• Statistical Tests:     29
• Visualizations:        15

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🚀 QUICK START
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1. Open final_report.html in any web browser for the interactive report
2. Load final_summary.json in Python/R for programmatic access
3. Browse figures/ for publication-quality visualizations
4. Analyze data/ CSV files with pandas, Excel, or R

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📧 Contact: Abbas Hamidavi
📅 Generated: 2026-07-28 20:15:45
