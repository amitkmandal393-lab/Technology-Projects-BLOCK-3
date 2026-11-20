# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot


(<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/6dcf52d7-94b7-4f9c-b9f9-029d948a3a85" />
)

### Questions

1.  Who owns the file?
2.  What are the default permissions?

### Reflection

Why is file ownership important in Linux systems?

------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

(<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/eb1277dc-c21a-4395-b2b8-5a3f137c15af" />
)

### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

(<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/51f5a89b-bb0d-4df3-81ad-0b7e775568f3" />
)

### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?

