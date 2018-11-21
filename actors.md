# FHIRcast actors

<small>*FHIR&reg; is the registered trademark of HL7 and is used with the permission of HL7.*</small>

The figure shows the actors involved in the FHIRcast protocol and the relevant transactions between them. 

>Actors are information systems or components of information systems that produce, manage, or act on information associated with operational activities in the enterprise. <br>
<sub>*Out of the [IHE Technical Framework](https://www.ihe.net/uploadedFiles/Documents/ITI/IHE_ITI_TF_Vol1.pdf)*</sub>

![actor diagram](out/actors.png)

The following table shows the actor and the transaction definitions. 

|Actor|Transaction|Opt.|Section|
|---|---|---|---|
|Hub|Subscribe|R||
|Hub|Unsubscribe|R||
|Hub|Event Notification|R||
|Client|Subscribe|R||
|Client|Unsubscribe|O||
|Client|Event Notification|R||

