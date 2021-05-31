# Systems Engineering &mdash; Design Brief
---

### Project name
Authenticated Door locking

### Project description
The basic idea of the project is to have some form of door lock, which allows access to authorized peoples through the use of a magnetic stripe on a card, rfid or knowlege of a code, use a keypad to disengage the systems lock temporarily, restricting access to sensitive areas.

### Preliminary research
From a look at the current widely used electronic doorlocks, all of them are integrated systems, having a solenoid or gear driven lock slug engaging with a depression in the door frame. These systems, which replace the typical passage set, often have keypads, key holes or card readers attached to the handle of the door. This allows for ease of interactivity as your hand is already positioned nearby. In some systems, a seperately mounted RFID card reader is used, allowing users to authorize themselves and then, once the door unlocks, get to where they need to be.

### Options

#### Option One
A traditional door lock, which engages, via the use of a lug propelled by solenoid, with a depression in the corresponding door frame. When a user with valid authorization interacts with a keypad, the 

Solenoid powered lug: 
![Solenoid powered lug](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages-na.ssl-images-amazon.com%2Fimages%2FI%2F51uEeBSnIjL._SL1100_.jpg&f=1&nofb=1)


#### Option two
A protrusion mounted to the door, which engages with an external housing for the lug on the exterior of the door frame. A user with valid authorization can, through the use of a keypad, retract the lug temporarily, allowing entry and exit.

#### Option three
Using a set of electromagnets, a door is kept locked due to the magnetic interaction between a piece mounted on the door, and an externally mounted 'locking piece'. A user with valid authorization can temporarily unpower these electromagnets, allowing the door to be opened.

Electromagnet system in use:
![Electromagnet lock](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Funionalarm.com%2Fwp-content%2Fuploads%2F2020%2F03%2F71Src8yDSCL._SL1181_.jpg&f=1&nofb=1)


### Chosen Option: One &mdash; Expansion
The door lock will be much like a traditional door lock, using a lug to engage with a resessed portion in the door. This lug will be propelled via a solenoid untill authorization is given. Authorization will be handled via an arduino in a keypad mounted to the exterior of the door. This keypad will accept a changeable code and a set of RFID cards, programmable by the device, alongside a master RFID key. The system will be battery operated for convenience, although whilst testing the device un-mounted and in a full scale deployment of this device, were it to be adapted to market, would be powered by mains power. The design will fit any door size as long as it uses a traditional passage set size.

### Evaluation criteria
* Size: The keypad is to fit within a 9cm x 7.5cm x 5cm casing
* Timing: The door is to unlock in less than two seconds
* UX: Users must be able to determine easily when their card is accepted / declined
* UX: The device must last serveral days on a single charge


### Timeline
| Term One                             | Term Two                            | Term Three (Constant) |
| :----------------------------------- | :---------------------------------- | :-------------------- |
| Fleshing out project idea.           | [31/5] Build mechanical model       | Test current design   |
| Proposing multiple ideas and goals   | [04/6] Mechanics testing            | Improve design        |
|                                      | [07/6] Authentication testing       | Docment changes       |
|                                      | [11/6] Debugging system             | Repeat above          |
|                                      | [14/6] Apply auth to model          |                       |


