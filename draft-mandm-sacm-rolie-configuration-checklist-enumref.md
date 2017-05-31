---
coding: utf-8

title: Enumeration Reference Format for Configuration Checklist Information
abbrev: rolie-cc-enumref
docname: draft-mandm-sacm-rolie-configuration-checklist-enumref-00
category: info

stand_alone: yes
pi: [toc, sortrefs, symrefs, comments]

author:
  -
    ins: B. Munyan
    name: Bill Munyan
    org: Center for Internet Security
    street: 31 Tech Valley Drive
    city: East Greenbush, NY
    code: 12061
    country: USA
    email: bill.munyan.ietf@gmail.com
  -
    ins: A. Montville
    name: Adam Montville
    org: Center for Internet Security
    street: 31 Tech Valley Drive
    city: East Greenbush, NY
    code: 12061
    country: USA
    email: adam.w.montville@gmail.com

--- abstract

Configuration checklist information can be represented using a number of XML data representations, such as the eXtensible Checklist Configuration Description Format (XCCDF), versions 1.1 and 1.2, Security Content Automation Protocol (SCAP) version 1.2 data-stream collections, and Open Vulnerability and Assessment Language (OVAL) definitions.

This document establishes a stand-alone data format to include both the external specification and specific enumeration identification value, and establishes an IANA registry to manage external enumeration specifications.

--- middle

{: #introduction}
# Introduction
TODO

{: #terminology}
# Terminology
TODO

{: #need-for-enumeration}
## The need for enumeration references
In the context of the "configuration-checklist", the `rolie:format` can reference numerous data serializations; different types of checklist content that can be utilized by consumers.  Consumers may only require a PDF version of the checklist, providing prose and descriptive information about the checklist and its recommendations.  Automation content consumers may have the ability to ingest and parse XML versions of the checklist in numerous forms, such as eXtensible Configuration Checklist Description Format (XCCDF) documents (of various versions), data-stream collections utilizing standards defined by the Security Content Automation Protocol (SCAP), or definitions written in the Open Vulnerability and Assessment Language (OVAL).  Publishers MAY provide configuration checklist formatted entries in any or all of these serializations, and consumers MAY choose to ignore those serializations which are not supported in their organizations or by their tooling.

{: #format-extension-point}
## rolie:format "configuration-checklist" Extension


