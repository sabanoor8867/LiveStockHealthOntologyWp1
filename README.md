# LiveStockHealthOntologyWp1
### [![DOI](https://zenodo.org/badge/659116364.svg)](https://zenodo.org/badge/latestdoi/659116364)

1: Create a standardized FAIR guideline framework that balances data requirements, accessibility, availability, connectivity, and value generation.

2: Design a Livestock Health Ontology (LHO) tailored to specific species, enriching knowledge graphs with domain expertise.

3: Convert raw cattle data into RDF format, harnessing RDF benefits for improved data sharing, integration, and querying.

4:Create a mapping process to match the cleaned RDF data with the species-specific LHO ontology, ensuring that the data can work together smoothly and be easily understood. You can find the code in R, PySpark, and Python notebooks here.

5: Implement a data visualization tool to analyze and report farm animal disease management data, empowering insightful decision-making and data interpretation.

We've made CattleUse work on three platforms: Python, R, and Pyspark. We did this by using data from different animal health service labs in Europe: DGZ, GD, Pathosen, Ireland, and ARSIA. Specifically, the DGZ lab's data works on all three platforms.
For ARSIA, PAthosen, Ireland, and GD labs:

. We used Panda in Python and R to implement the ARSIA lab's data.

. Similarly, we used Panda in Python and R for the Pathosen lab's data.

. The Ireland lab's data also works using the Panda library in both Python and R.

. Lastly, the GD lab's data is functional with Panda in both Python and R.

In summary, while the Pyspark implementation was showcased with the DGZ dataset, the same methodology was followed for the remaining datasets (GD, Pathosen, ARSIA, and Ireland), albeit without a separate Pyspark demonstration. In the 'UnionOfAllRDF.ipynb' notebook, we aggregate RDF data from DGZ, Pathosen, Ireland, GD, and ARSIA Labs. This process involves combining RDF files from these sources into a unified representation. The resulting unified RDF representation is then utilized in visualization tools for example Tableau for comprehensive analysis.

| Platforms         |          Lab1             |	     Lab2             |	      Lab3	            |      Lab4           |	    Lab5              |
| ------------------| -------------------------| -------------------- |-----------------------------| -----------------------| ------------------------|
| Python Panda      | [Lab1DataPandacode.ipynb ](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab1DataPandacode.ipynb) | [Lab2DataPandaCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab2DataPandaCode.ipynb)  |[Lab3DataPandaCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab3DataPandaCode.ipynb) |[Lab4Pandacode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab4DataPandaCode.ipynb)| [Lab5DataPandaCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab5Pandacode.ipynb)|
| R                 | [Lab1DataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab1DataRCode.ipynb)      | [Lab2DataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab2DataRCode.ipynb)    | [Lab3DataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab3DataRCode.ipynb)     | [Lab4RCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab4DataRCode.ipynb)     | [Lab5DataRCode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab5DataRCode.ipynb)    |
| PySpark           | [Lab1DataPysparkcode.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/Lab1DataPysparkCode.ipynb) |----------------------|-----------------------------| -----------------------| ------------------------|
| Union of All RDF  | -------------------------|-[UnionOfAllRDF.ipynb](https://github.com/decide-project-eu/LiveStockHealthOntologyWp1/blob/main/UnionofAllRDF.ipynb)--|-----------------------------|------------------------|-------------------------|




