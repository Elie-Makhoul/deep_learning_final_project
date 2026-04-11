==============================================================================
DEEP LEARNING
==============================================================================

Project Files                                # Deep Learning Final Project Folder
│
├── data/                                    # Project datasets and metadata
│   ├── part_1/                              # Data used for Part 1 (image classification)
│   │   ├── Flicker8K_Dataset_7zip/          # Compressed Flickr8k dataset files
│   │   ├── Flickr8k_text/                   # Flickr8k text and metadata files
│   │   ├── train_image_class.csv            # Training image-label mapping file
│   │   └── valid_image_class.csv            # Validation image-label mapping file
│   │
│   └── part_2/                              # Data used for Part 2 (financial text prediction)
│       ├── SEC_Data_7zip (1)/               # Split compressed SEC filings data files
│       ├── SEC_Data_7zip (2)/               # Split compressed SEC filings data files
│       └── SP500_RiskFactors_Dataset.zip    # Compressed S&P 500 risk factors dataset file
│
├── docs/                                    # Project documentation
│   ├── requirements/                        # Course requirements and supporting material
│   │   ├── best_practices_CNN.pdf           # CNN best practices reference
│   │   ├── extra_info.pdf                   # Additional project information
│   │   ├── final_presentation.pdf           # Course final presentation file
│   │   └── guideline.pdf                    # Project guidelines and requirements
│   │
│   ├── report_1/                            # Part 1 written report
│   │   └── deep_learning_report_1.pdf       # Flickr image classification report
│   │
│   ├── report_2/                            # Part 2 written report
│   │   └── deep_learning_report_2.pdf       # Financial sequence prediction report
│   │
│   └── presentation/                        # Final project presentation slides
│       └── deep_learning_presentation.pdf   # Deep Learning final presentation
│
└── src/                                     # Main development notebooks
    ├── part_1/                              # Source files for Part 1
    │   └── deep_learning_part_1.ipynb       # Flickr image classification notebook
    │
    └── part_2/                              # Source files for Part 2
        ├── deep_learning_part_2.ipynb       # Financial sequence prediction notebook
        └── scraping_part_2.ipynb            # SEC data scraping and preprocessing notebook