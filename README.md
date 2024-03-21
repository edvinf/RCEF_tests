# RCEF_tests
Proof of concept tests for candidate format for national / regional catch estimation

Contains code demonstrating that candidate format for national / regional catch estimation for RDBES/TAF can support some stock coordination tasks. Code is part of intersessional work for WGRDBESGOV (WGRDBESGOV_ISSG_RCEF).

## Structure
The directory 'data' contains estimates formatted in candidate formats as rds files:
* estimates_caa.rds estimates of Norwegian harvest of North Sea Herring in 2022 for a single activity domain
* estimates_caa.rds estimates of Norwegian harvest of North Sea Herring in 2022 for activity domain corresponding to gears
* estimates_caa.rds estimates of Norwegian harvest of North Sea Herring in 2022 for activity domain corresponding to gears, with estimates only provided for some gears

The directory 'demonstrations' contain code demonstrating that the format can be used for various stock-coordination purposes.

The directory 'reports' contain generated reports from other directories like 'demonstrations'. While these may be html formatted, your browser may not render them when clicked on github. Download and open to view.

Run the script generate_reports.R generate reports.