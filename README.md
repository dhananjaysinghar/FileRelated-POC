
GO TO DEV CLINE:
-----------------
1. This is the prompt which we are providing here in dev cline to generate synthetic data.

2. Once we trigger, This request, it's routed through the MCP server to the backend API.




3. Now I would like to show the REST API which internally called by MCP Server.


SWAGGER PAGE:
-----------------
4. This is the swagger for our Synthetic Data Generator API's.
5. Here we have 3 endpoint's like generate , evaluate and visualize.



SWAGGER PAGE GENERATE METHOD:
-----------------------------
6. The Generate API takes real data as input. Using OpenAI, it analyzes the data and creates a metadata file, which we use in SDV library to generate synthetic data.
7. Once data generated we are storing those in S3 bucket along with metadata file which created by OpenAI at runtime.



GOTO AWS CONSOLE:
---------------------
8. Here's an example of the metadata file stored in S3. [AWS]

9. If you see here in metadata file we have multiple tables and the relationship between these two tables. [AWS]

10. And Here the generated data files. [AWS]




INTELIJ:
-----------
11 Now that the data generation is completed, Now I will show the data quality METRICS and distribution analysis.

12. This chart compares the real data vs. synthetic data, showing a normal distribution with no skew, closely matching the original.


13 . Here's the data quality report—it's above 80%, which indicates a high level of accuracy.


14. Now I would like to hand over to Navneet for Benefits and Future actions
