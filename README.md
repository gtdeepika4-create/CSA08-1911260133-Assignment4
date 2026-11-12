[Uploading README.md…]()
# CSA08-1911260133-Assignment4

**Student:** Deepika Gopu  
**Register number:** 1911260133  
**Course:** Python Programming – CSA08  
**Course code:** CSA0803  
**Python:** 3.10+ (standard library only)

## Repository contents

- `Task1_File_Processing/` – robust mess-file processing with `Decimal` and rejected-row tracking.
- `Task2_Biometric_Attendance/` – daily CSV attendance processing, duplicate detection, summary, below-75% report and error log.
- `Task3_Exception_Handling/` – custom exception, nested handling and file-level exception handling.
- `Task4_File_Forensics/` – append-only returns log and error log.
- `Task5_Utility_Organisation/` – the same attendance utility shown as one script, one reusable module, three modules and a package.
- `Task6_Fest_Registration/` – multi-department registration processing, duplicate merging, event files and error report.

## Run the tasks

Run each command from its task folder. Python 3.10 or later is recommended.

```bash
cd Task1_File_Processing && python task1_mess_file.py
cd ../Task2_Biometric_Attendance && python task2_attendance.py
cd ../Task3_Exception_Handling && python task3_exceptions.py
cd ../Task4_File_Forensics && python task4_returns.py
cd ../Task5_Utility_Organisation/01_single_script && python attendance_one.py
cd ../02_reusable_module && python main.py
cd ../03_three_modules && python main.py
cd ../04_package && python main.py
cd ../../Task6_Fest_Registration && python task6_registration.py
```

The programs create their output files in the current task folder (or the documented output subfolder). Some demonstration scripts create small synthetic input files when run. Task 6 deliberately includes only Arts and Science input files so the program demonstrates handling the other three missing department files.

## GitHub submission steps

1. Create a **public or faculty-accessible** repository named `CSA08-1911260133-Assignment4`.
2. Upload the complete contents of this folder.
3. Replace the GitHub URL placeholder on the cover page of the assignment report with the repository URL.
4. Commit each task separately so the repository history shows progressive work. Suggested commit messages: `Add Task 1 file processing`, `Add Task 2 attendance processing`, and so on through Task 6.
5. Add fresh screenshots captured from your own runs if your faculty requires execution evidence.

**Repository URL:** _Add your GitHub repository URL here after creating it._

## Notes

- All examples use Python's standard library; no third-party packages are required.
- Input data are synthetic demonstration data, not actual student records.
- Run and verify all programs on your computer before submission.
