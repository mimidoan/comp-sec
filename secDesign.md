# Lecture 2 - Computer Security Design

There are no "Laws" to system Design. There are best practices, but no absolutes.

### Fundamental Design Principles
  * open design - talking & engaging to people about your design
  * keep it simple - the more complicated your system is, the more likely that there are imperceptible flaws in the hierarchy
    * complexity != Security
  * Modularity - can be adapted to new threats
  * Principles of least astonishment - system behaves the way users expect it to

### Principles of secure design
  * Principle of minimizing secrets
    * secrets should be few & changeable, and system should not need to be modified if secret must be changed
    * Security should not depend on secrecy of design
      "security through obscurity" --> like putting a backdoor in and assuming that no one will find it
  * Principle of complete mediation
  * Principle of fail-safe defaults
    * make it so that a system is secure by default, no extra configs should be necessary
  * Principle of least privilege
    * only give access that is needed, and that access can be taken away after utilizations
  * Principle of economy of mechanism
  * Principle of least common mechanism
    * mechanisms used to access resources should not be accessible to all

# Ethics

Worms are malware that replicate themselves and spread to other computers
  - white worms patch the holes that it finds
