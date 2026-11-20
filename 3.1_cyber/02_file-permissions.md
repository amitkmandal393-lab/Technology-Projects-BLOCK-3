# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/6bf00173-18de-496b-97a4-ad906c2c37a7" />

()

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

(Add screenshot here)

### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot

(Add screenshot here)

### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?

