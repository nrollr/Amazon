## re:Invent 2018

The AWS re:Invent Session catalogue can be consulted through the  [re:Invent portal](https://www.portal.reinvent.awsevents.com), though access may be decommissioned in the near future. Hence a copy of the catalogue for future reference. 

The session catalogue is available in **`.SQL`** and **`.JSON`** format. (based on standard [RFC 4627](https://www.ietf.org/rfc/rfc4627.txt?number=4627)). 

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
* Entries representing `Overflow`-sessions have been renamed to remove the venue reference (eg. **AIM301-ROFA** is now AIM301-R-OF1, where the   **`OF1`**-suffix corresponds to `overflow session number 1`.
* Not included (for now) are the links to media (eg. video, audio, slides).. might be added soon