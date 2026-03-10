dl-course-project/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── docs/ # GitHub Pages website
│ ├── index.md # home page
│ ├── assignment1.md
│ ├── assignment2.md
│ ├── assignment3.md
│ └── assets/
│ ├── images/
│ └── videos/
│
├── assignments/
│ ├── assignment1/
│ │ ├── notebooks/
│ │ │ ├── image/
│ │ │ ├── text/
│ │ │ └── multimodal/
│ │ │
│ │ ├── results/
│ │ │ ├── figures/
│ │ │ └── tables/
│ │ │
│ │ ├── demo/
│ │ └── README.md
│ │
│ ├── assignment2/
│ │ ├── notebooks/
│ │ ├── results/
│ │ ├── demo/
│ │ └── README.md
│ │
│ └── assignment3/
│ ├── notebooks/
│ ├── results/
│ ├── demo/
│ └── README.md
│
├── reports/
│ ├── assignment1/
│ │ ├── report1.pdf
│ │ └── final_report.pdf
│ │
│ ├── assignment2/
│ │ └── report.pdf
│ │
│ └── assignment3/
│ └── report.pdf
│
└── shared/ # optional reusable utilities
├── dataloaders.py
├── metrics.py
└── training_utils.py
