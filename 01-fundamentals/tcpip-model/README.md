# The TCP/IP Model

TCP/IP stands for Transmission Control Protocol / Internet Protocol. This model has 4 layers. It is the set of rules that the internet follows today.

The TCP/IP model is simpler than the OSI model. It combines some OSI layers together into one layer.

---

## Layer 4: The Link Layer (sometimes called Network Access Layer)

**Job:** To handle the physical hardware and the local network.

This layer is a combination of Layer 1 (Physical) and Layer 2 (Data Link) from the OSI model. It deals with cables, network cards, and MAC addresses.

**Examples:** Ethernet, Wi-Fi, network switches.

---

## Layer 3: The Internet Layer

**Job:** To send data across different networks and find the best path.

This layer does the same job as Layer 3 (Network) in the OSI model. It uses IP addresses to route data from one computer to another anywhere in the world.

**Examples:** IP addresses (IPv4 and IPv6), routers, the IP protocol.

---

## Layer 2: The Transport Layer

**Job:** To manage the delivery of data between two programs on different computers.

This layer does the same job as Layer 4 (Transport) in the OSI model. It decides whether to send data reliably (with checking) or quickly (without checking).

**Examples:** TCP (reliable, checks for errors), UDP (fast, no error checking).

---

## Layer 1: The Application Layer

**Job:** To provide rules that user programs follow to exchange data.

This layer is a combination of Layer 5 (Session), Layer 6 (Presentation), and Layer 7 (Application) from the OSI model. It includes the data format, the encryption, and the program rules all in one place.

**Examples:** HTTP (web browsing), SMTP (email), FTP (file transfer), DNS (domain name lookup).

---

## How the TCP/IP layers compare to the OSI layers

This table shows how the two models line up.

| TCP/IP Layer | What it includes from the OSI model |
|--------------|--------------------------------------|
| Application (Layer 1) | OSI Layers 5, 6, and 7 (Session, Presentation, Application) |
| Transport (Layer 2) | OSI Layer 4 (Transport) |
| Internet (Layer 3) | OSI Layer 3 (Network) |
| Link (Layer 4) | OSI Layers 1 and 2 (Physical, Data Link) |

---

## A simple way to remember the TCP/IP layers

From the top layer (closest to the user) to the bottom layer (the physical hardware):

**All Travellers Like Italy**

- **A**pplication
- **T**ransport
- **L**ink (Internet layer - just remember that "Like" stands for the Internet layer)
- **I**nternet

Or more accurately from top to bottom:

**All Travellers Use Internet?** (Yes, they do)

- **A**pplication
- **T**ransport
- **U**se (stands for Internet layer)
- **I**nternet (but wait, this repeats... better to use:)

**A Tiger Is Large** (from top to bottom)

- **A**pplication
- **T**ransport
- **I**nternet
- **L**ink

---

## Which model is more important?

Both models are taught in networking courses. However, the TCP/IP model is the one that the internet actually uses. The OSI model is more of a teaching tool. If you want to understand how the real internet works, focus on the TCP/IP model.

---

## Summary table

| Layer Position | Layer Name | Simple job |
|----------------|------------|-------------|
| Top (Layer 1) | Application | Rules for user programs (includes session and presentation jobs) |
| Layer 2 | Transport | Deliver data safely or quickly |
| Layer 3 | Internet | Route data across the world using IP addresses |
| Bottom (Layer 4) | Link | Handle the physical cables and local network |