# benign-marker-class

A single compiled Java class (P.class, bytecode 52 / Java 8) whose static
initializer sleeps for 8 seconds and does nothing else. Used as a timing
marker during an AUTHORIZED penetration test to prove that a server-side
deserialization flaw performs remote class loading. No exploit logic, no
data access, no persistence.
