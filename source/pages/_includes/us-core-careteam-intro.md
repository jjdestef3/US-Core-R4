This profile sets minimum expectations for the [CareTeam] resource for identifying the Care Team members associated with a patient. It identifies which core elements, extensions, vocabularies and value sets **SHALL** be present in the resource when using this profile.

**Example Usage Scenarios:**

The following are example usage scenarios for the US Core-CareTeam profile:

-   Query for a Patient's CareTeam
-   [Record or update] a Patient's CareTeam


### Mandatory and Must Support Data Elements


The following data-elements are mandatory (i.e data MUST be present) or must be supported if the data is present in the sending system ([Must Support] definition). They are presented below in a simple human-readable explanation.  Profile specific guidance and examples are provided as well.  The [Formal Profile Definition] below provides the  formal summary, definitions, and  terminology requirements.  

**Each CareTeam must have:**

1.  a patient
1.  a participant role for each careteam members
1.  names of careteam members which can be:
    -   a practitioner (doctor, nurse, therapist)
    -   the patient
    -   a relative or friend or guardian
    -   an organization

**Each Condition must support:**

1.  a status code

**Profile specific implementation guidance:**

* none

### Examples

- [CareTeam-example](CareTeam-example.html)


[CareTeam]:  {{site.data.fhir.path}}careteam.html

{% include link-list.md %}
