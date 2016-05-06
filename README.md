# tsi-tsom-bppm-integration
BMC TrueSight Intelligence integration with TSOM and BPPM for services, data/metrics and events

## Configuration
Integration Requirements:
The following are required for this integration:
Pentaho PDI 6.1 or later - Kettle (Open Source ETL)
Java SE (JRE) – no specific version required
BPPM +9.5,  TSIM +10
Embedded Sybase Database
Service Models – can be created via Atrium CMDB, Direct Publishing or Manual Creation
*Oracle is supported by replacing the following transformation:  TSI_Metric_Creation_REST_API_from_BPPM_TSIM_Step1.ktr which is included in the zip below named "TSI_Metric_ETL_Step_for_TSIM_BPPM_with_Oracle_backend.zip". Also read the Readme document for 2 steps.
