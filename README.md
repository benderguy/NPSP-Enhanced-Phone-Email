# NPSP-Enhanced-Phone-Email
Enhanced phone and email workflow rules for use with the Salesforce Nonprofit Starter Pack


This is XML that can be copied directly into Eclipse. It contains Contact validation rules, workflow rules and field updates which can replace (or in some cases, work in along side) the similar ones that come with the NPSP. These were built to enhance usability of the phone & email "preferred" fields so that they made logical automated choices whenever possible.

These will default the "Preferred Phone" or "Preferred Email" field to a particular phone or email selection. When only one phone/email is filled in, it becomes the preferred one automatically. Validation rules will also force manual selection of a preferred option when there are more than one selected. This is how the phone ones are set up by default if you simply use this xml as-is.

Alternatively, you can also create a priority hierarchy, which is how the email one is set up by default with this package of functionality. This means that when no preferred email is chosen, workflow will automatically choose one based on a hierarchy (work if it is not blank, then home if it is not blank, then alt if it is not blank, etc.) If a preferred choice is made, then it is not overridden.
