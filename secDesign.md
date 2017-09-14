# Lecture 2 - Computer Security Design

## There are no "Laws" to system Design

 There are best practices, but no absolutes.

### Fundamental Design Principles
  * open design - talking & engaging to people about your design
  * keep it simple - the more complicated your system is, the more likely that there are imperceptible flaws in the hierarchy
    * complexity != Security
  * Modularity - can be adapted to new threats
  * Principles of least astonishment - system behaves the way users expect it to

### Principles of secure design
  * Principle of minimizing secrets
    ..* secrets should be few & changeable, and system should not need to be modified if secret must be changed
    ..* Security should not depend on secrecy of design
      "security through obscurity" --> like putting a backdoor in and assuming that no one will find it
    ..*
  * Principle of complete mediation
  * Principle of fail-safe defaults
  * Principle of least privilege
  * Principle of economy of mechanism
  * Principle of least common mechanism
