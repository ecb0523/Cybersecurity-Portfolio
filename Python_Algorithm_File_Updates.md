# Python: Automated Access Control Update

## Project Description
This project demonstrates an automation script designed to manage access to restricted content by updating an "allow list" of IP addresses. It automates the removal of unauthorized IPs, ensuring the system remains secure without manual intervention.

## Technical Summary
- **Language:** Python
- **Key Functions:** `open()`, `.read()`, `.split()`, `.remove()`, `.join()`, `.write()`
- **Methodology:** Used a `with` statement for secure file handling and a `for` loop to iterate through a "remove list" to cross-reference against the "allow list."

## Step-by-Step Execution
1. **Open & Read:** The script opens the `allow_list.txt` in read mode.
2. **Parsing:** The content is converted from a string into a list for easy manipulation.
3. **Filtering:** Iterated through the list to identify and remove IPs matching the `remove_list`.
4. **Update:** The updated list is joined back into a string and rewritten to the file, replacing the old entries.

## Impact
Automating this process reduces human error and ensures that access permissions are updated in real-time as security requirements change.
