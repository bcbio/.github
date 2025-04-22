# Notes

## 📝 **Meeting Summary 2025-04-22

**Committee:** Phil Ewels, Lukas Weber, Geraldine Van der Auwera

Meetings Notes:
- Integration with nf-core: everybody agreed that this project could be part of nf-core as a new type of element in the community
- We decided to focus on templates with guidelines for analysts. Templates will assume nf-core output folder structure with documentation for customization.
- We included Shiny apps as part of the resources.
- Test data can come from nf-core full AWS examples, Bioconductor Experiment Hubs, and nf-core small data-sets
- Propose next steps:
   - Documentation on how to contribute/develop resources
  - Documentation on how to use them, what are the first steps, using one template-report as an exmaple.
 
Sure! Here's a rewritten version of your meeting summary with improved context, clarity, and references/links for relevant resources:

---

### 🔗 Integration with nf-core

The team agreed that our project aligns well with the mission and structure of [nf-core](https://nf-co.re/), the community-driven platform for standardized bioinformatics pipelines.
As such, it could be integrated into nf-core as a new category of resource — specifically, a toolkit of reusable reporting resources for data analysts.

This new resource type could expand nf-core's value to end users by providing pre-built tools for downstream result visualization and interpretation,
adhering to the same best practices and versioning policies as existing pipelines.

---

### 📋 Standardized Templates for Reports

The project will focus on creating customizable reporting templates, guided by best-practice documentation. These templates are designed for analysts and will:

- Assume the standardized nf-core output folder structure.
- Include documentation for adjusting and extending templates to meet different project needs.
- Provide structured guidance to simplify adoption across the community.

Reference on output structure: https://nf-co.re/usage/output_structure
Example of template: https://github.com/bcbio/rnaseq-reports/blob/main/01_quality_assessment/QC.Rmd
Interesting resources: https://github.com/marimo-team/marimo-pixi-starter-template/tree/main

---

### 📊 Incorporating Visualization Tools (e.g. Shiny apps)

Shiny applications (built with R’s shiny package) will be included as part of the reporting toolkit. These apps can serve as interactive and user-friendly front ends to explore pipeline results. The goal is to create a plug-and-play ecosystem where end users can easily generate meaningful summaries post-pipeline execution.

---

### 🧪 Sourcing and Supporting Test Data

To support development and use of templates, we identified several reliable sources of test data:

- nf-core full pipeline test datasets hosted on AWS S3 (e.g., via https://nf-co.re/pipelines)
- Bioconductor's ExperimentHub (https://bioconductor.org/packages/ExperimentHub/)
- nf-core datasets for small test runs (e.g., https://github.com/nf-core/test-datasets)

These resources will help ensure reproducibility and facilitate robust testing of templates and visualizations.

---

### ✅ Next Steps

To move forward, the team proposed the following priority actions:

1. 📚 Create documentation on how users can contribute to or develop new reporting resources.
    - This will include templates for contributions, standards, code formatting, resource submission process, etc.
    - Coordinate with nf-core core team to initiate the plan for merging with nf-core resources

2. 🚀 Develop user documentation on how to use the reporting templates.
    - This guide will walk users through starting with a sample template-report.
    - Include "first steps," such as launching a template with nf-core outputs, expected inputs, and customizing parameters.

---

We'll continue coordinating implementation through GitHub discussions and updates to the project repository. 
For collaboration and feedback, please join the nf-core Slack workspace (https://nf-co.re/join) and channel #nf-core-reports

Let us know if you'd like to contribute or if you have feedback on these next steps!

--- 

