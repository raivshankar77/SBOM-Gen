### TELEMETRY SBOM & CVE Generator

The TELEMETRY SBOM & CVE Generator supports firmware security assessment for industrial use cases. Through a graphical interface, users can generate a Software Bill of Materials (SBOM) from extracted firmware or analyse an existing SBOM to identify known vulnerabilities (CVEs) and prioritize them according to industrial use-case requirements.

The tool integrates the open-source [cve-bin-tool](https://github.com/intel/cve-bin-tool) into a workflow tailored to TELEMETRY project requirements and industrial partners’ use cases and operational scenarios.

**A planned update will add CVE prioritization linked to the Devices Under Test (DUTs) and automated assessment workflows used in the TELEMETRY project.
**
**Key features**

- SBOM generation from extracted firmware.
- CVE identification from firmware or an existing SBOM.
- CVE prioritization according to industrial use-case requirements.
- Human-readable HTML reports.

Results support further assessment: reported CVE matches require validation in the device’s deployment context, and an absence of findings does not establish that firmware is secure.
