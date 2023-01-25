# TMoIP in Serial

The TMoIP serial is a serial type starting with "T" (case insensitive). This type uses a specific set of settings.

## DQE ALignment

Derived property meaning the frame sync is `FAC4`. Enabling this property does the following.

- Set frame sync to `FAC4`
- Set sync length to `16`
- Set variable length to `not-applicable` (hide)
- Changes `Frame Length` labels to `DQE Packet Size (bits)`
- Changes `Buffer Size` labels to `DQE Buffer Size (bytes)`
- Setpass data to `not-applicable` (hide)
- Changes subcategory labels for "Framing" to "Packet"

> [See also Base.md section TMoIP channels](\Base.md)
