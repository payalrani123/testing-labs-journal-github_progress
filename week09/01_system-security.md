# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

(!<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/fd3e0337-edb9-42bd-a067-d04e846fce1b" />
)

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

### Screenshot

(Add screenshot here)

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

(Add screenshot here)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
