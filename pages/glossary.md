---
layout: page
body-class: page
title: "Glossary"
permalink: /glossary/
---

This page describes domain-specific
terminology used when designing or re-designing Public Services,
and when working with the Touchpoints product.

* Service Design - the specification and construction of processes that delivers valuable capacities for action to a particular customer.
* Organization - a federal government agency, or division of an agency
* Service - a means of delivering value to customers by facilitating outcomes customers want to achieve
  * a Service has one or more Actors (people or systems)
  * a Service has sequential and/or concurrent Events
  * a Service has one or more Channels
* Channels - a specific medium in which a customer interaction occurs. Examples include: email, phone, website
* Service Event - an individual Event within a defined Service
  * any given Service Event may have an associated Touchpoint
* Touchpoint (generically) - where an interaction between a service provider and customer occurs
* Touchpoints (in the context of Federal Service design) - a software product that provides the ability to capture feedback, in the form of digital Touchpoints
  * a Touchpoint displays a Form. That Form is selected from a list of approved FormTemplates.
* Form - one instance of a Form for one Touchpoint
  * a Form is based on a Form Template
  * a Form is customizable

### Delivering a Touchpoint to a Web Page

* Tag Container - provided by Google Tag Manager, that contains the following objects
  * Tag - customizable code (usually html, css, js) - to add behaviors and styles to a page that includes this Tag's Container
    * a Tag lives within a Container
    * many Tags can live within a Container
    * a Tag is often used to hold a script that loads a Touchpoint
  * Trigger - conditions to display or evaluate a given Tag
  * Variable - a variable defined with GTM that can be re-used within GTM

### Delivering a Touchpoint via Email

* location_code - The URL parameter `?location_code=` can be used to identify what location a Submission relates to, if a a single Touchpoint is deployed for a service that spans multiple Locations.

### Reporting on websites and Public Services (service designed services)

* Analytics - includes general website analytics (like DAP) and Service Design analytics
* Events - a specific interaction or event fired from a webpage. Typically, on button click or page event
* Goals - a sequence or combination of events to trigger
* Conversions - measurement regarding a specific goal. For examples: 1) 50% of users who click through to Sign Up, complete the Sign Up, or 2) 10% open-rate for emails

### Organizational Maps & Artifacts

Many types of artifacts can be used to help
model and communicate about Services
when practicing Service Design.

Admittedly, there is a lot of overlap between artifacts and there are [many perspectives](https://medium.com/leading-service-design/service-mapping-and-different-types-of-maps-604a1a22e22c)
about formats and formal structure of design artifacts.
However, our team is primarily interested
on building the shared understanding required
to drive outcomes supporting improved public service delivery.
These artifacts serve as maps of a territory,
but are not to be confused with the territory itself.

* Sequence Diagram - how objects pass messages back and forth, as a sequence of events
* Organizational Chart - the hierarchy or linked structure on an Organization's Staff
* Service Blueprint - a formalized Service diagram, including Front-stage, Back-stage, and Supporting Services
* Journey Map - a user-centric description of events across a given "Journey"; for example; the sequenced steps and obvservations of a user when signing up for a Vehicle Registration
* Wardley Map - a value stream mapped across product/service maturity
* Concept Model - a node graph of concepts

<div class="usa-alert usa-alert-info">
  <div class="usa-alert-body">
    <p class="usa-alert-text">
      View Touchpoints documentation to learn about the
      <a href="https://github.com/GSA/touchpoints/wiki/Data-Model" target="_blank" rel="noopener">Data Model</a>  
      and more.
    </p>
  </div>
</div>
