================================================================================
HUARAVITO RESERVE LTEMS - RAW DATASETS COLLECTION
================================================================================

Version: 1.0
Release Date: February 2026
Custodian: Randall Santamaría Artavia
Site: Huaravito Reserve Long-Term Ecological Monitoring Site (LTEMS)
Location: Piedades Sur, San Ramón, Alajuela, Costa Rica
Coordinates: 10.1065°N, 84.5666°W | 1,250 m.a.s.l.

================================================================================
OVERVIEW
================================================================================

This collection contains four primary raw datasets from the Huaravito Reserve 
LTEMS, established in 2021 to monitor microclimatic stability, forest structure, 
and biodiversity dynamics in a premontane forest fragment.

All datasets are:
  ✓ Structured for external review and academic collaboration
  ✓ Maintained in archival formats (CSV, TXT)
  ✓ Accompanied by comprehensive metadata documentation
  ✓ Released under Creative Commons Attribution 4.0 (CC BY 4.0)

================================================================================
DATASETS INCLUDED
================================================================================

01. TEMPERATURE LOGS (2022-2025)
    File: 01_temperature_logs.csv
    Metadata: 01_temperature_logs_METADATA.txt
    Description: 4 years of continuous monthly mean temperatures
    Records: 48 months
    Key Finding: -3.7°C sustained biogenic cooling effect

02. TREE CENSUS (2026 Baseline)
    File: 02_tree_census_2026.csv
    Metadata: 02_tree_census_METADATA.txt
    Description: Complete structural inventory of permanent 30×30m plot
    Records: 25 trees ≥10 cm DBH
    Key Finding: 60% Hauya elegans dominance; 1,667 trees/ha density

03. SOIL ORGANIC LAYER (2026 Baseline)
    File: 03_soil_organic_layer.csv
    Metadata: 03_soil_organic_layer_METADATA.txt
    Description: Organic layer depth at 10 permanent sampling points
    Records: 10 points
    Key Finding: 21.8 cm mean depth; high fungal activity

04. BIODIVERSITY MASTER RECORD (2021-2026)
    File: 04_biodiversity_master_record.csv
    Metadata: 04_biodiversity_master_record_METADATA.txt
    Description: iNaturalist-validated species observations (representative sample)
    Records: 25 observations (sample); 238 total in full iNaturalist dataset
    Key Finding: 116 species documented; 72 Hauya elegans observations

================================================================================
SITE CONTEXT
================================================================================

The Huaravito Reserve LTEMS is a 5,800 m² forest fragment in the premontane 
zone of Costa Rica's Central Valley. The site is notable for:

  • Exceptional thermal homeostasis (σ ~0.2°C interannual variance)
  • Documented 10.2°C thermal gradient (degraded land to forest core)
  • High density of Hauya elegans (Guayabón), a regionally rare tree
  • Presence of epiphytic orchids indicating primary forest conditions
  • Integration with multiple monitoring platforms (iNaturalist, Terraware, 
    Restor, NASA GLOBE Observer)

The LTEMS operates under the Sentinel Protocol, which governs site protection, 
data continuity, and long-term stewardship commitments.

================================================================================
DATA USE GUIDELINES
================================================================================

LICENSE:
All datasets are released under Creative Commons Attribution 4.0 International 
(CC BY 4.0). You are free to:
  • Share: Copy and redistribute in any medium or format
  • Adapt: Remix, transform, and build upon for any purpose, including commercial

Under the following terms:
  • Attribution: You must give appropriate credit, provide a link to the license, 
    and indicate if changes were made

RECOMMENDED CITATION:
Santamaría Artavia, R. (2026). Raw Datasets Collection (2021-2026), Huaravito 
Reserve Long-Term Ecological Monitoring Site, Costa Rica. Huaravito Reserve 
LTEMS. Dataset version 1.0.

ATTRIBUTION EXAMPLES:

For academic papers:
  "Temperature data from Huaravito Reserve LTEMS (Santamaría Artavia 2026) 
   show sustained biogenic cooling of -3.7°C..."

For reports:
  "Tree density calculations based on Huaravito LTEMS tree census data 
   (Santamaría Artavia 2026)..."

For datasets derived from this collection:
  "Source: Huaravito Reserve LTEMS Raw Datasets v1.0 (Santamaría Artavia 2026)"

================================================================================
DATA QUALITY AND LIMITATIONS
================================================================================

STRENGTHS:
  ✓ Multi-year temporal coverage (2021-2026)
  ✓ Standardized protocols with documented methods
  ✓ Georeferenced observations
  ✓ Cross-platform validation (iNaturalist, Terraware, etc.)
  ✓ Transparent metadata documentation

LIMITATIONS:
  ⚠ Single-sensor microclimatic monitoring (no spatial replication)
  ⚠ Visual height estimation (no clinometer)
  ⚠ Qualitative assessments (moisture, fungal presence)
  ⚠ Consumer-grade GPS (±5-10 m precision)
  ⚠ Small spatial extent (single plot; opportunistic biodiversity sampling)
  ⚠ Baseline year only for tree census and soil data (no temporal replication yet)

These limitations are explicitly documented in individual metadata files.

================================================================================
FUTURE UPDATES
================================================================================

The LTEMS is committed to long-term monitoring with the following schedule:

  • Temperature Logs: Continuous (updated annually)
  • Tree Census: Re-measurement every 2 years (next: 2028)
  • Soil Organic Layer: Re-measurement annually (next: 2027)
  • Biodiversity: Ongoing iNaturalist observations

Dataset versions will be incremented with each major update:
  v1.0 (Feb 2026) - Baseline release
  v2.0 (Feb 2027) - First annual update
  v3.0 (Feb 2028) - Second tree census integration
  ...and so on

================================================================================
RELATED DOCUMENTATION
================================================================================

For contextual information and interpretation, refer to:

  1. LTEMS Monitoring Framework (2026-2031)
     Comprehensive protocol document

  2. Biogenic Thermal Buffering - Preliminary Report (Feb 2026)
     Documents the 10.2°C thermal gradient observation

  3. Hauya elegans Population Analysis (Feb 2026)
     Species-specific analysis and old-growth hypothesis

  4. Technical Data Annex
     Consolidated summary with tables and visualizations

  5. Proposed Mechanisms of Biogenic Cooling (Feb 2026)
     Theoretical framework for observed thermal stability

All available upon request or via the Huaravito Reserve LTEMS website.

================================================================================
TECHNICAL SPECIFICATIONS
================================================================================

FILE FORMATS:
  • CSV: Comma-separated values (UTF-8 encoding)
  • TXT: Plain text metadata (UTF-8 encoding)

CSV CONVENTIONS:
  • Header row: Column names (no spaces; underscores for multi-word names)
  • Decimal separator: Period (.)
  • Date format: YYYY-MM-DD (ISO 8601)
  • Missing data: Empty cell or "NA"
  • Comments: Lines beginning with "#" (temperature logs only)

GEOGRAPHIC COORDINATES:
  • Datum: WGS84
  • Format: Decimal degrees
  • Precision: 5 decimal places (~1 m resolution)

SOFTWARE COMPATIBILITY:
  These datasets are compatible with:
    - Microsoft Excel / Google Sheets (spreadsheet analysis)
    - R (statistical analysis: read.csv())
    - Python pandas (data analysis: pd.read_csv())
    - QGIS / ArcGIS (spatial analysis with GPS coordinates)
    - Any text editor (metadata review)

================================================================================
CONTACT INFORMATION
================================================================================

Data Custodian:
  Randall Santamaría Artavia
  Custodian-Director, Huaravito Reserve LTEMS
  Piedades Sur, San Ramón, Alajuela, Costa Rica
  Email: [Insert contact email]

Institutional Affiliation:
  Independent ecological monitoring initiative
  Integrated with: iNaturalist, Terraware, Restor, FERM (FAO), NASA GLOBE Observer

Collaboration Inquiries:
  Academic researchers, students, and institutions interested in collaboration 
  or data use are encouraged to contact the custodian. Data sharing agreements 
  for unpublished data or collaborative projects can be arranged.

================================================================================
ACKNOWLEDGMENTS
================================================================================

This monitoring initiative is made possible by:
  • Long-term site stewardship and daily custodial presence
  • iNaturalist community for taxonomic verification
  • Global Forest Watch and Restor for satellite data integration
  • SNAPP-MORE Working Group (University of Minnesota) for collaboration
  • Open-source software communities (R, Python, QGIS)

Special recognition to:
  • The Guayabón trees (Hauya elegans) for existing
  • The Toyopán Sacred Forest for persisting in a fragmented landscape
  • All observers who contribute to the iNaturalist project

================================================================================
VERSION HISTORY
================================================================================

v1.0 (February 2026):
  - Initial release
  - Temperature logs: 48 months (2022-2025)
  - Tree census: Baseline (2026)
  - Soil organic layer: Baseline (2026)
  - Biodiversity: 5-year summary (2021-2026)

================================================================================
END OF README
================================================================================

For the latest version of this dataset collection, visit:
  iNaturalist: https://www.inaturalist.org/projects/reserva-huaravito-sitio-natural-sagrado
  Restor: https://restor.eco/es/sites/c4c9b69f-1f0b-40bc-9d80-2d18fd1e54cf
  Terraware: https://terraware.io/species?organizationId=213

Last updated: 2026-02-26
