# The OSI Model

OSI stands for Open Systems Interconnection. This model has 7 layers. Each layer has a specific job.

The layers are numbered from the bottom to the top. Layer 1 is the physical hardware. Layer 7 is where the user interacts with the network.

---

## Layer 1: The Physical Layer

**Job:** To send raw signals through a physical medium.

This layer deals with cables, connectors, and network cards. It sends bits (0s and 1s) as electrical signals, radio waves, or light pulses.

**Examples:** Ethernet cables, fibre optic cables, Wi-Fi radio signals.

---

## Layer 2: The Data Link Layer

**Job:** To move data between two devices on the same network.

This layer organises bits into frames. It also checks for errors that may have happened at the Physical Layer.

**Examples:** MAC addresses (the unique address of your network card), switches.

---

## Layer 3: The Network Layer

**Job:** To move data between different networks.

This layer finds the best path for data to travel from the source to the destination. It can cross routers and travel across the internet.

**Examples:** IP addresses (like 192.168.1.1), routers.

---

## Layer 4: The Transport Layer

**Job:** To make sure data arrives completely and in the right order.

This layer breaks large data into smaller pieces. It also checks if any pieces are missing. If something is missing, it asks for it again.

**Examples:** TCP (reliable delivery), UDP (fast delivery).

---

## Layer 5: The Session Layer

**Job:** To start, manage, and end a conversation between two devices.

This layer keeps different conversations separate. For example, your web browser and your email program can talk to the same computer without mixing up the data.

**Examples:** Session IDs, login sessions.

---

## Layer 6: The Presentation Layer

**Job:** To translate, encrypt, or compress data.

Different computers may store data in different ways. This layer makes sure that both computers understand the same format. It can also scramble (encrypt) data for safety or shrink (compress) it to save space.

**Examples:** SSL/TLS encryption, JPEG image conversion, file compression.

---

## Layer 7: The Application Layer

**Job:** To provide services directly to the user's software.

This layer is closest to the user. It is not the application itself (like a web browser). Rather, it is the rules that the application follows to use the network.

**Examples:** HTTP (for websites), SMTP (for email), FTP (for file transfers).

---

## A memory trick

To remember the 7 layers from bottom to top, try this sentence:

**Please Do Not Throw Sausage Pizza Away**

- **P**hysical
- **D**ata Link
- **N**etwork
- **T**ransport
- **S**ession
- **P**resentation
- **A**pplication

---

## Summary table

| Layer Number | Layer Name | Simple job |
|--------------|------------|-------------|
| 7 | Application | Rules for user programs |
| 6 | Presentation | Translate, encrypt, compress |
| 5 | Session | Start and end conversations |
| 4 | Transport | Deliver data safely |
| 3 | Network | Find the best path |
| 2 | Data Link | Move data on the same network |
| 1 | Physical | Send raw signals |