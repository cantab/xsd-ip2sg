# XSD IP2SG

XML Schema Definitions for creating frmx files for batch uploading to IP2SG.

## Introduction
IPOS' IP2SG electronic online system allows patent, trade mark, design or common forms to be uploaded using the "batch upload" function, *in lieu* of manual form filling.

In order to be processed by the batch upload function, the form and any attachments must be packaged into a single file. The format of this file must conform to Microsoft's Open Packaging Conventions (OPC).

This repository contains the XSD files describing the structure of the XML in the forms need to create .frmx packages.

## Frmx OPC File Format

An OPC package contains one or more folders. Each folder represents one IP2SG form and any attachments associated with the form.

Within each folder, there is a single XML file containing the form data. If the form has any attachments, these are also contained in the folder.

The OPC package also contains an OPC relational file.

## Acknowledgements

- [IP2SG Batch Filing Announcement](https://www.ip2.sg/RPS/Common/Announcements.aspx?id=81)
