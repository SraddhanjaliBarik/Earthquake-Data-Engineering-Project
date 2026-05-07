# Earthquake-Data-Engineering-Project
Built an end-to-end data engineering and analytics solution for earthquake event analysis using Microsoft Fabric, implementing a Medallion architecture (Bronze, Silver, Gold) within a Lakehouse environment to ensure scalable, reliable, and structured data processing.

Data was ingested from earthquake event sources through Fabric Data Pipelines and stored in the Bronze layer as raw data. Using Fabric Notebooks, data cleansing, transformation, and enrichment were performed in the Silver layer, including handling missing values, standardizing formats, and deriving key attributes such as magnitude categories and depth classifications.

The curated Gold layer was designed for analytical consumption, aggregating earthquake trends by region, time, and severity. A semantic model was built to define business-ready metrics and ensure consistency across reporting layers.

Finally, interactive dashboards were developed in Power BI to visualize earthquake frequency, magnitude distribution, and geographic hotspots, enabling meaningful insights into seismic activity patterns.

The solution also incorporates data lineage, monitoring, and governance features within Microsoft Fabric to ensure data quality, traceability, and reliability across the pipeline.
