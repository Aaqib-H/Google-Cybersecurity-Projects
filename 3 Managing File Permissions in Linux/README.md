# Managing File Permissions in Linux

## Project Description
This project demonstrates the process of configuring file and directory permissions for a research team in a large organization to ensure only authorized users have appropriate access. By examining and modifying file permissions in the Linux file system, I aligned access rights with the organization’s authorization requirements to enhance data security.

## Scenario
As a security professional assigned to support a research team, part of my role is to ensure that team members have the correct file permissions for their project directories. After auditing the permissions in the `/home/researcher2/projects` directory, I discovered that unauthorized users had access to sensitive files and directories. My task was to modify these permissions using Linux commands to secure the system and ensure data confidentiality.

## Tools Used
- **Linux Command Line**
- **`ls -la`**: Listed all files, including hidden ones, with detailed permissions.
- **`chmod`**: Modified permissions for user, group, and other to secure files and directories.

## Skills Learned
- Interpreting Linux permission strings and their impact on data security
- Using `ls -la` to inspect permissions on files, directories, and hidden files
- Applying `chmod` commands to configure permissions for users, groups, and others
- Securing sensitive files and directories by removing unauthorized access

## Project Steps:

1. **Auditing File and Directory Permissions**:
   - Checked permissions of files and directories under `/home/researcher2/projects` using `ls -la`.
   - Verified that sensitive files were exposed to unauthorized users, requiring adjustments.

2. **Understanding Permissions Strings**:
   - Reviewed the 10-character permissions strings (e.g., `drwxrwxrwx`) to determine access rights for each file and directory.
   - Identified that files and directories had inappropriate permissions, especially for the "other" category.

3. **Updating Permissions**:
   - Used `chmod` commands to modify permissions, such as removing write access for unauthorized users in "other" for sensitive files.
   - Adjusted permissions for the hidden file `.project_x.txt` to restrict access while preserving necessary read permissions for the user and group.
   - Removed execute permissions from the "group" for the `drafts` directory to limit access to only the intended user.

### Final Permissions Configuration:
- Files and directories were reconfigured to ensure that only authorized users have the necessary permissions. Unauthorized "other" access was removed to prevent potential security breaches.

## Documentation
![1](https://github.com/user-attachments/assets/7a3f15e7-e069-4d5d-a4d7-7b3a22df1027)
![2](https://github.com/user-attachments/assets/2ddf9fcb-ed7a-46af-a34d-97c8843bcc30)
![3](https://github.com/user-attachments/assets/7d59ee26-8318-45bc-a32c-1adbc41f8932)
![4](https://github.com/user-attachments/assets/2da6b1dd-08cf-447e-85be-7a0ed678929c)



## Project Outcome
Through this project, I successfully updated file and directory permissions to meet authorization standards, ensuring that only authorized team members have access to sensitive data within the research team’s directory. This improved the organization’s security posture by preventing unauthorized access to critical files and directories.


## Supporting Documents
- [Current File Permissions Report](https://github.com/Aaqib-H/Google-Cybersecurity-Projects/blob/main/3%20Managing%20File%20Permissions%20in%20Linux/Current%20File%20Permissons.docx)
