# open-scada-rs
Open Supervisory control and data acquisition (SCADA) platform developed in Rust. Focusing on platform security and reliability.
<br/><br/><br/>

## Main focus
The main focus for this project is to develop a control and data acquisition system that takes advantage of the latest technologies available. Providing a safe, robust and performant system that can be used for multiple purposes requiring data acquisition and processing.
<br/><br/>

----
## Basic Architecture
The system is mainly composed of a server process that can be run on any platform satisfying the basic requirements, and multiple clients. The main purpose of each is:
- Server: Process inputs received from clients, update an internal real-time database and update data to subscribing clients.
- Clients: Acquire data from multiple sources and transmit to server, receive updates from server and update its outputs.

![open-scada-rs server architecture image](https://raw.githubusercontent.com/josesantosPT/open-scada-rs/main/docs/img/open-scada-rs-architecture.svg "open-scada-rs server architecture")
