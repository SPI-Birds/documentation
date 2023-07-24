<h1 style="font-weight:normal" align="center">
  &nbsp;SPI-Birds Network and Database: Documentation&nbsp;
</h1>

<div align="center">

&nbsp;&nbsp;&nbsp;
<a href="https://spibirds.org"><img border="0" alt="Blog" src="https://assets.dryicons.com/uploads/icon/svg/4926/home.svg" width="40" height="40"></a>&nbsp;&nbsp;&nbsp;
<a href="mailto:spibirds@nioo.knaw.nl"><img border="0" alt="Email" src="https://assets.dryicons.com/uploads/icon/svg/8007/c804652c-fae4-43d7-b539-187d6a408254.svg" width="40" height="40"></a>&nbsp;&nbsp;&nbsp;
<a href="https://twitter.com/spibirds"><img border="0" alt="Twitter" src="https://assets.dryicons.com/uploads/icon/svg/8385/c23f7ffc-ca8d-4246-8978-ce9f6d5bcc99.svg" width="40" height="40"></a>
&nbsp;&nbsp;&nbsp;

</div>

<h3 style="font-weight:normal" align="center">
  &nbsp;Welcome to the documentation repository for the SPI-Birds Network and Database. Follow the links above to visit our website, contact us via e-mail or Twitter. This README is an overview of the various documents produced by SPI-Birds.&nbsp;
</h3>

---

# Introduction

The SPI-Birds Network and Database aims to create a global network of Studies on Populations of Individual birds (SPI-Birds), improving data accessibility and transparency, and facilitating collaboration and data reuse. As part of this project we build robust [data pipelines](https://github.com/SPI-Birds/pipelines) for different researchers and research groups that return their primary data in a standard format. We envision that this standard format will facilitate greater collaboration by allowing data from multiple populations to be easilty collated and compared.

The documents created as part of the SPI-Birds Network and Database are structured in folders. Below you will find an overview of the documents that can be found in each of the folders.

# Documents

## Standard protocol

The main documentation produced by the SPI-Birds Network is the [standard format](https://github.com/SPI-Birds/documentation/tree/master/standard_protocol), a standard protocol for the collection of individual-level bird data, defined and shaped by the community of bird researchers. This protocol is the foundation of the [data pipelines](https://github.com/SPI-Birds/pipelines) that convert data owners' primary data format into SPI-Birds' standard data format, as well as as a guideline for people who wish to establish a new field site for monitoring individual birds.

SPI-Birds developers and the Network are continuously working to update and fine-tune the standard format to the needs of the user community. The latest version of the standard protocol is [version 2.0.0](https://github.com/SPI-Birds/documentation/blob/master/standard_protocol/SPI_Birds_Protocol_v2.0.0.pdf), released in March 2023.

## Quality check

The [data quality check](https://github.com/SPI-Birds/documentation/tree/master/quality_check) is a second procedure part of the SPI-Birds workflow. After pipelines have been constructed in tight collaboration with the people who have custody over the data, the integrity and quality of the data are checked. This quality check procedure identifies suspicious records and flags them either as *potential errors* or *warnings*. *Potential errors* are values considered impossible (e.g., negative values for clutch size); *warnings* are values considered unlikely (e.g., larger brood size than the number of chick records present) and are thus less severe than *potential errors*.

The latest version of the quality check is [version 1.1.1](https://github.com/SPI-Birds/documentation/blob/master/quality_check/SPI-Birds_quality-check-protocol_v1.1.1.pdf), released in July 2023. Note: the quality check procedure is designed for pipelines built according to version 1.0.0 and version 1.1.0 of the standard format; a quality check procedure for pipelines built according to version 2.0.0 is under construction.

## Terms and conditions

The terms and conditions folder contains three documents.

### Terms of use

The [terms of use](https://github.com/SPI-Birds/documentation/blob/master/terms_and_conditions/SPI-Birds_Terms-of-Use.pdf) document is designed to guide the use of data hosted at SPI-Birds Database. Members of the SPI-Birds Network endorse that data hosted at SPI-Birds can be requested for academic, research, education, and other non-profit professional purposes. To facilitate data reuse whilst acknowledging data custody, the document includes a data user agreement and guidelines for attribution.

### Data licenses

The [data licenses](https://github.com/SPI-Birds/documentation/blob/master/terms_and_conditions/SPI_Birds_Data_Licenses.pdf) document describes the three license options that data custodians may select when contributing their data to the SPI-Birds Database. The document describes these licenses and draws similarities to various Creative Commons licenses where relevant.

### Metadata information

We invite everyone who runs a field study on individually marked birds to join the SPI-Birds Network by contributing metadata (including details on the study site, data coverage, data custody, and protocols used in data collection). The [metadata information](https://github.com/SPI-Birds/documentation/blob/master/terms_and_conditions/SPI_Birds_Metadata-Information.pdf) document describes what SPI-Birds does with these metadata, and what rights the contributor has when joining SPI-Birds.

## Newsletter

The SPI-Birds [newsletter](https://github.com/SPI-Birds/documentation/tree/master/newsletter) is a semi-regular newsletter to inform the members of the Network about technical developments (e.g., updates on the standard format), collaborations, grant applications, and meet-ups at conferences and other events. 

# Bugs, ideas or requests?

Have you detected bugs in any of our documents or codes? Are you missing valuable variables in the standard format, or do you have any requests for additional quality checks? Feel free to share these with us here ([Create New Issue](https://github.com/SPI-Birds/documentation/issues/new/choose)) or in our [pipelines repository](https://github.com/SPI-Birds/pipelines).
