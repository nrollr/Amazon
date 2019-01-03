## re:Invent 2018

The AWS re:Invent session catalogue can be accessed through the  [re:Invent portal](https://www.portal.reinvent.awsevents.com), though access may be decommissioned in the near future. Hence a copy of the catalogue for future consultation. 

The session catalogue is available in **`.SQL`** and **`.JSON`** format. (JSON based on standard [RFC 4627](https://www.ietf.org/rfc/rfc4627.txt?number=4627)). 

**JSON stucture :** 

``` json
{
  "catalogue": {
    "sessions": [
      {
        "id": "value",
        "session": "value",
        "title": "value",
        "description": "value",
        "topic": "value",
        "level": "value",
        "type": "value",
        "schedule": {
          "day": "value",
          "timeslot": "value"
        }
      }
    ]
  }
}
```
##### Remarks
* References to the venues where the sessions took place, are not included.
* Entries representing `Overflow`-sessions have been renamed to remove the venue reference: eg. **AIM301-ROFA** is now AIM301-R-**OF1** (where the   **OFx**-suffix corresponds to overflow session number).

##### To Do list
* At this stage media links are not included (eg. video, audio, slides).
* At this stage the only included session types are: `Builder session`, `Chalk talk`, `Overflow`, `Session` & `Workshop`