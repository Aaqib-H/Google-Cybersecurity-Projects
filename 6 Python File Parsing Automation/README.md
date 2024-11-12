# Python File Parsing Automation

## Project Description
In this project, I developed a Python algorithm to automate the process of updating a file containing the allow list of IP addresses that have access to restricted content in a health care organization. The algorithm checks whether any IP addresses from a remove list are present in the allow list and removes them, ensuring that only authorized IP addresses retain access.

## Scenario
As a security professional, I was tasked with regularly updating a file that identifies employees allowed to access restricted content. This list, stored in the `allow_list.txt` file, is based on employees who are authorized to work with personal patient records. A separate `remove_list` contains IP addresses that need to be removed from the allow list due to various reasons. My task was to create a Python algorithm to update the allow list by removing IP addresses present in the remove list.

## Tools Used
- **Python**: Developed the algorithm to manipulate the allow list and remove list.
- **File Handling**: Used Python’s built-in methods to read and write to text files.
- **Lists**: Utilized lists to store and manipulate IP addresses.
- **Loops and Conditionals**: Implemented a `for` loop to iterate through the remove list and conditionals to filter out IP addresses.
- **String Methods**: Used `.split()`, `.join()`, and `.read()` methods to handle file contents.

## Skills Learned
- Automating file updates using Python.
- Reading and writing to text files.
- Manipulating strings and lists in Python.
- Using loops and conditionals to process data.
- Ensuring data integrity by removing unauthorized IP addresses.

## Project Steps:
1. **Open the `allow_list.txt` File**:
   - Opened the `allow_list.txt` file using the `with open()` statement and read its contents.
   
2. **Read the File Contents**:
   - Used the `.read()` method to convert the contents of the file into a string format for further processing.

3. **Convert the String into a List**:
   - Split the string into a list of IP addresses using the `.split()` method to facilitate the removal of specific IPs.

4. **Iterate Through the Remove List**:
   - Implemented a `for` loop to iterate through the `remove_list` and identify which IPs should be removed from the allow list.

5. **Remove IP Addresses from the List**:
   - Used `.remove()` to eliminate IP addresses from the `allow_list` that matched any in the `remove_list`.

6. **Update the File with the Revised List**:
   - Converted the list back into a string using the `.join()` method and wrote the updated list back to the `allow_list.txt` file using the `.write()` method.

## Documentation
<img src="https://github.com/user-attachments/assets/8ec5d36f-77c5-4a4c-9474-e271186e3392" width="600" />
<img src="https://github.com/user-attachments/assets/821d0242-ba75-4007-b4e5-c14bf08069bd" width="600" />
<img src="https://github.com/user-attachments/assets/fb2afc78-adc1-4708-a395-5c09d6af8594" width="600" />
<img src="https://github.com/user-attachments/assets/15450b70-5e7a-45dd-8bc5-53dc51444b8d" width="600" />
<img src="https://github.com/user-attachments/assets/bf75b712-fc6e-483b-8872-cf7173cd0042" width="600" />

## Project Outcome
By creating this Python algorithm, I automated the process of updating the `allow_list.txt` file. The algorithm effectively checks the remove list and removes unauthorized IP addresses from the allow list, ensuring that only authorized employees retain access to sensitive patient records. This solution improved the efficiency of managing restricted access in the organization and minimized the potential for human error.
