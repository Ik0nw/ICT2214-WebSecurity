# ICT2214-WebSecurity
Repository for scripts in Assignment 1 in partial fulfillment for ICT2214 Web Security

## .Har files
The har files directory contains .har files of APKs that are found to have transmitted personal data to domains.
These .har file contains network traffic with personal identifiable data inside. 
These network traffic are captured by Reqable and LibChecker during Phase 3: Dynamic Analysis.
You may download Reqable to open the .har files and analyze the network traffic within these files.

## Scripts
These Python scripts are created for Phase 2: Static Analysis

To use full_static_scan.py, change the target directory where all APKs are located and set a target directory to store all the text files.

Run the script using the following command:
```
python3 full_static_scan.py
```

To use sensitive_finding.py, change the target directory and set it to the directory where all the text files are stored.

Run the script using the following command:
```
python3 sensitive_finding.py
```

# Author
Ik0nw
