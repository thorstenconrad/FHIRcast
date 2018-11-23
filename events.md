# FHIRcast Events

<small>*FHIR&reg; is the registered trademark of HL7 and is used with the permission of HL7.*</small>

This document describes the events used in FHIRcast, that can be occur and subscribed to. 

Event               |Description
--------------------|---
open-patient-chart  |User opened patient's medical record.
close-patient-chart |User closed patient's medical record.
switch-patient-chart|User changed from one open patient's medical record to another previously opened patient's medical record. The context documents the patient whose record is currently open.
open-imaging-study  |User opened record of imaging study.
switch-imaging-study|User changed from one open imaging study to another previously opened imaging study. The context documents the study, and optionally patient, for the currently open record.
close-imaging-study |User closed imaging study.
user-logout         |User gracefully exited the application.
user-hibernate      |User temporarily suspended her session. The user's session will eventually resume.
