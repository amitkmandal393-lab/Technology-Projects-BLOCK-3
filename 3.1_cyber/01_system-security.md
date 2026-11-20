# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/25c4d0e8-80d2-4fa3-a31b-7572a5756394" />






### Questions

1.  How many users exist on the system?
2.  Which accounts appear to be system accounts?
3.  Why do operating systems create system accounts?

### Reflection

Explain why understanding system users is important for cybersecurity.

------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

(<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/6beb39b2-9fdd-4186-a8a0-9366478898f7" />
)

### Questions

1.  Which processes are running as `root`?
2.  Why can processes running as root be dangerous?
3.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(
)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
