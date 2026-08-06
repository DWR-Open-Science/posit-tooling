# Posit at DWR

This repository contains documentation related to a pilot of [Posit products](https://posit.co) at the California Department of Water Resources (DWR).

The pilot is being pursued in response to recurring staff requests for easier ways to build, run, and publish modern data science products using [R](https://www.r-project.org), [Python](https://www.python.org), and related open-source tools.

In particular, staff have expressed a need for:

* **Straightforward publishing of analytical products**, especially Shiny applications, without requiring each team to design and maintain its own deployment process
* **Easy access to enhanced computing resources** for analyses that exceed the capabilities of an individual workstation
* **Modern, supported data science development environments** for R, Python, Jupyter, Positron, Visual Studio Code, and related tools
* **Better pathways for sharing analytical work** with colleagues, decision makers, partners, and other audiences
* **More consistent support for reproducible and collaborative data science workflows**

The pilot is intended to evaluate whether a shared Posit platform can meet these needs effectively at DWR.

The pilot runs through June 30, 2027.

This repository serves as a central reference for people participating in, supporting, sponsoring, or learning about the pilot. It will include information about the products being evaluated, intended uses, user guidance, governance considerations, and lessons learned during the pilot.

## Why DWR is piloting Posit

DWR staff increasingly use R, Python, Shiny, Quarto, Jupyter, and other open-source technologies for scientific analysis, data engineering, visualization, reporting, and application development.

These tools are powerful, but several common challenges arise when staff want to move beyond work performed on an individual computer.

For example, an analyst may be able to build a useful Shiny application locally but have no simple way to make it available to colleagues. A scientist may need more computing power or memory than is available on a standard workstation. Teams may also want access to modern development environments without individually assembling and maintaining the underlying tooling.

To address these barriers, at a high level, the pilot is investigating whether DWR can provide staff with:

* A supported place to conduct modern data science;
* Access to computing resources beyond an individual workstation;
* A simple path from development to publication;
* A shared environment for collaboration and reproducibility; and
* An organizational framework for managing the resulting analytical products.

One of the most important use cases is **low-friction publishing**. For supported content types, the goal is to make publishing closer to a routine part of the analytical workflow rather than a separate software deployment project.

For a Shiny developer, for example, the desired experience is that an application developed and tested in the data science environment can be published to an appropriate audience with a relatively simple ("one-click") publishing workflow.

The pilot will help DWR determine how well this model works in practice and what governance, support, and operational practices would be needed if use of the platform expands.

## What is being piloted

The pilot includes two primary Posit products: **[Posit Workbench](https://posit.co/products/enterprise/workbench)** and **[Posit Connect](https://posit.co/products/enterprise/connect)**.

Together, they support two closely related needs: creating data science products and making those products available to others.

### Posit Workbench

Posit Workbench provides a shared development environment for data science.

It gives staff browser-based access to tools commonly used for R and Python development, including environments such as [RStudio](https://posit.co/products/open-source/rstudio), [Jupyter](https://jupyter.org), [Positron](https://positron.posit.co), and [Visual Studio Code](https://code.visualstudio.com), paired with enhanced compute.

For pilot participants, Workbench is intended to evaluate whether DWR can provide easier access to:

* Modern R and Python development tools
* Centrally available computing resources
* Compute and memory beyond what may be available on a standard workstation
* Reproducible analytical environments
* Collaborative data science workflows
* Development of applications, reports, dashboards, and other products using frameworks such as [Shiny](https://shiny.posit.co) and [Streamlit](https://streamlit.io)
* A straightforward path for publishing appropriate work through Posit Connect

A major question for the pilot is whether providing these resources centrally can reduce the amount of effort individual staff and programs spend configuring and maintaining their own analytical environments and address friction in compute-intensive workflows.

Workbench is primarily the **development and computing side** of the pilot.

### Posit Connect

Posit Connect provides a platform for publishing and managing data science products.

It allows staff to take work developed in R, Python, and other supported frameworks and make it available through a web browser.

Content may include:

* Shiny applications
* Interactive dashboards
* [Quarto](https://quarto.org) and [R Markdown](https://rmarkdown.rstudio.com) reports
* Python applications
* Static documents and websites
* APIs
* Scheduled or automatically refreshed analytical products
* Scheduled email reports

For the pilot, one of Connect's most important capabilities is its ability to make publishing substantially easier than building a separate hosting solution for every analytical product.

Rather than requiring a Shiny developer to become responsible for web server configuration, containerization, application hosting, and other deployment infrastructure, Connect provides a standardized publishing workflow designed specifically for data science content.

This **develop → publish → share** workflow is one of the central capabilities DWR is evaluating.

Connect is primarily the **publishing and delivery side** of the pilot.

## Workbench and Connect together

The two products are designed to support a simple workflow.

A typical example might look like this:

1. A staff member develops an analysis or application using R or Python in a modern data science environment, with access to appropriate computing resources.
2. Source code and supporting materials are maintained in a reproducible form, typically using version control.
3. When the product is ready to share, it is published through Posit Connect.
4. Colleagues, other authorized users, or the general public access the resulting application, report, dashboard, or API through a web browser.
5. The author can update the product as the underlying analysis or data changes.

Not every analysis needs to be published, and not every project will follow exactly the same workflow. The broader goal is to reduce unnecessary technical barriers between analytical work and its intended users.

## What the pilot is intended to learn

The pilot is not simply a software installation. It is an opportunity to determine whether these tools meet real needs across DWR and what would be required to support them sustainably.

Questions the pilot may help answer include:

* Do staff find the development environments useful and accessible?
* Does access to shared compute improve analytical workflows?
* Does the platform materially simplify publishing Shiny applications and other data products?
* What types of products are staff interested in publishing?
* What support do new users need?
* What governance is appropriate for published applications and other content?
* How should product ownership and maintenance responsibilities be defined?
* What accessibility, security, and review practices should apply to published products?
* Which use cases are well suited to Posit, and which are better served by other DWR technologies?
* What level of demand exists across programs?
* What would be required to operate the environment sustainably if DWR decides to continue or expand its use?

Experience from pilot users will help inform these decisions.

## Who the pilot is for

The pilot platform will be useful to several groups across DWR.

**Scientists** can use it to work with R and Python, access additional computing resources, and create and publish analytical products. Initially, 10 scientists have developer seats in the pilot.

**Programs and project teams** can use published applications, dashboards, reports, and other products to support internal workflows and communicate analytical information. Initially, up to 100 accounts are available for viewing private published products. Products can also be published publicly, without access or identity restrictions.

**Managers and executive sponsors** may primarily encounter the platform through the products created by staff. From this perspective, Posit provides a way for analytical work developed by DWR staff to become usable applications and resources without every project requiring a bespoke technology stack.

**Technology, security, accessibility, and governance staff** can help evaluate how the platform fits within DWR's broader technology environment and what practices would be necessary for sustainable administration.

## What this repository will document

This repository is intended to serve as the documentation hub for the Posit pilot.

Topics may include:

* Pilot goals and scope
* Pilot process documents, such as meeting agendas and notes
* Guidance for participating in the pilot
* Instructions for obtaining access
* Publishing workflows
* Expectations for application and content owners
* Security and data handling considerations
* Support and troubleshooting information
* Governance questions and decisions
* Feedback from pilot users
* Lessons learned and recommendations resulting from the pilot

Detailed infrastructure documentation may be maintained separately where appropriate.

## What Posit does—and does not—provide

Posit can simplify several parts of the data science workflow, particularly development, access to compute, and publication.

It does not eliminate the broader responsibilities associated with creating and operating a DWR analytical product.

Depending on the product and its audience, staff may still need to consider:

* Data governance
* Information security
* Accessibility
* Privacy
* Records and retention requirements
* Source code management
* Testing
* Documentation
* Appropriate review and approval
* Long-term product ownership

Part of the purpose of the pilot is to determine how these responsibilities should be addressed without recreating unnecessary barriers to publishing and sharing useful analytical work.
