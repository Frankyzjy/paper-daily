---
name: Research Interests
about: Configure paper search topics
title: Research Interests
labels: config
assignees: ''
---

```json
{
  "sources": [
    { "type": "arxiv", "name": "arXiv" }
  ],
  "conference_sources": {
    "enabled": true,
    "include_default_venues": false,
    "current_year": 2026,
    "lookback_years": 2,
    "venues": [
      {
        "id": "isca",
        "name": "ISCA",
        "enabled": true,
        "group": "computer architecture",
        "dblp_toc_patterns": ["db/conf/isca/isca{year}.bht"]
      },
      {
        "id": "micro",
        "name": "MICRO",
        "enabled": true,
        "group": "computer architecture",
        "dblp_toc_patterns": ["db/conf/micro/micro{year}.bht"]
      },
      {
        "id": "hpca",
        "name": "HPCA",
        "enabled": true,
        "group": "computer architecture",
        "dblp_toc_patterns": ["db/conf/hpca/hpca{year}.bht"]
      },
      {
        "id": "asplos",
        "name": "ASPLOS",
        "enabled": true,
        "group": "computer architecture",
        "dblp_toc_patterns": [
          "db/conf/asplos/asplos{year}-1.bht",
          "db/conf/asplos/asplos{year}-2.bht",
          "db/conf/asplos/asplos{year}-3.bht",
          "db/conf/asplos/asplos{year}-4.bht"
        ]
      },
      {
        "id": "mlsys",
        "name": "MLSys",
        "enabled": true,
        "group": "systems for machine learning",
        "dblp_toc_patterns": ["db/conf/mlsys/mlsys{year}.bht"]
      },
      {
        "id": "eurosys",
        "name": "EuroSys",
        "enabled": true,
        "group": "systems",
        "dblp_toc_patterns": ["db/conf/eurosys/eurosys{year}.bht"]
      }
    ]
  },
  "topics": [
  {
    "id": "environmental_microbiology_metagenomics",
    "name": "Environmental Microbiology and Metagenomics",
    "description": "Focus on environmental microbiology, microbial ecology, microbiomes, shotgun metagenomics, metagenome-assembled genomes (MAGs), microbial interactions, and genome-resolved analyses in natural and engineered environments.",
    "keywords": [
      "environmental microbiology",
      "microbial ecology",
      "environmental microbiome",
      "metagenomics",
      "shotgun metagenomics",
      "genome-resolved metagenomics",
      "metagenome assembled genomes",
      "MAGs",
      "microbial community",
      "functional annotation",
      "comparative genomics",
      "population genomics",
      "microbial diversity",
      "microbial evolution"
    ],
    "arxiv_categories": [
      "q-bio.GN",
      "q-bio.QM"
    ]
  },

  {
    "id": "water_quality_aquatic_ecosystems",
    "name": "Water Quality and Aquatic Ecosystems",
    "description": "Focus on freshwater ecosystems, river and watershed processes, aquatic ecology, water pollution, water quality assessment, and microbial dynamics in aquatic environments.",
    "keywords": [
      "water quality",
      "freshwater ecology",
      "river ecosystem",
      "aquatic ecosystem",
      "watershed",
      "watershed management",
      "surface water",
      "river microbiome",
      "aquatic microbiology",
      "water pollution",
      "ecological assessment",
      "river restoration",
      "environmental monitoring"
    ],
    "arxiv_categories": [
      "q-bio.PE",
      "q-bio.QM"
    ]
  },

  {
    "id": "environmental_health_one_health",
    "name": "Environmental Health and One Health",
    "description": "Focus on environmental health, One Health approaches, pathogen surveillance, microbial risk assessment, human exposure pathways, and public health implications of environmental contaminants and microorganisms.",
    "keywords": [
      "One Health",
      "environmental health",
      "public health",
      "health risk assessment",
      "microbial risk assessment",
      "pathogen surveillance",
      "waterborne pathogens",
      "human exposure",
      "environmental epidemiology",
      "disease transmission",
      "environmental pathogens",
      "zoonotic pathogens"
    ],
    "arxiv_categories": [
      "q-bio.QM",
      "q-bio.PE"
    ]
  },

  {
    "id": "emerging_contaminants_wastewater_treatment",
    "name": "Emerging Contaminants and Wastewater Treatment",
    "description": "Focus on wastewater treatment technologies, advanced oxidation processes, emerging contaminants, pharmaceuticals, PFAS, resource recovery, and sustainable water treatment systems.",
    "keywords": [
      "wastewater treatment",
      "water treatment",
      "advanced oxidation process",
      "AOP",
      "selective oxidation",
      "emerging contaminants",
      "contaminants of emerging concern",
      "PFAS",
      "pharmaceuticals",
      "micropollutants",
      "resource recovery",
      "membrane technology",
      "wastewater reuse",
      "industrial wastewater"
    ],
    "arxiv_categories": [
      "physics.chem-ph"
    ]
  },

  {
    "id": "environmental_antimicrobial_resistance",
    "name": "Environmental Antimicrobial Resistance",
    "description": "Focus on antibiotic resistance genes, environmental resistomes, antimicrobial resistance dissemination, mobile genetic elements, horizontal gene transfer, and resistance risks in environmental systems.",
    "keywords": [
      "antibiotic resistance genes",
      "ARGs",
      "antimicrobial resistance",
      "AMR",
      "environmental resistome",
      "resistome",
      "mobile genetic elements",
      "plasmids",
      "horizontal gene transfer",
      "integrons",
      "environmental AMR",
      "multidrug resistance",
      "resistance dissemination",
      "Acinetobacter"
    ],
    "arxiv_categories": [
      "q-bio.GN",
      "q-bio.MN"
    ]
  },

  {
    "id": "global_change_water_resources",
    "name": "Global Change and Water Resources",
    "description": "Focus on climate change impacts on water systems, hydrology, ecohydrology, watershed processes, water security, droughts, floods, and interactions between global environmental change and aquatic ecosystems.",
    "keywords": [
      "global change",
      "climate change",
      "hydrology",
      "ecohydrology",
      "water resources",
      "water security",
      "watershed processes",
      "drought",
      "flood",
      "extreme weather",
      "climate adaptation",
      "river basin",
      "land use change",
      "ecosystem resilience"
    ],
    "arxiv_categories": [
      "physics.geo-ph",
      "q-bio.PE"
    ]
  }
]
}
```
```
