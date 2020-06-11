# ADA-Lab-2
ADA Laboratory Work Nr.2 st.gr. TI-191M Iuzvac Anatolie

# Decoupling

**Coupling** describes the degree of dependency between one entity to another entity. Loose coupling is good because we don't want the components of our system to heavily depend on each other. We want to keep our system modular, where we can safely change one part without affecting the other.

When two parts are loosely coupled, they are more independent of each other and are less likely to break when the other changes. Most important factor of **Decoupling** is to create a system with minimum dependencies and minimum assumptions.

**Temporal Decoupling** is used to decouple components in way that changes/remove/addition of components does not disrupt the work of other components

**Spatial Decoupling** is used to decouple components which can be located in any place and work together as a system.

# Decoupling Use Cases

1. **Payment system** in a project I work on, is working based on **Temporal Decoupling** which provides stability and security in implementation of payment flow in the project.
2. **Mail Server** was created in a project I work on, on a different server than the server where the Main Backend System is stored and running, they intercommunicate between them using **SMTP** and **IMAP** Mail protocols with enabled **TLS** therefore using **Spatial Decoupling**.
3. **Backend for routing between two locations** created in a project I work on, on a different server than the server where the Main Backend System is stored and running, this server is setup fully to intercept two location points with latitude and longitude and give the response the distance and the route in points to be shown on map in front-end view and has stored on itself huge loads of map information of one country therefore using **Spatial Decoupling**.




