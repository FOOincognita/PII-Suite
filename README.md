# PII-Suite 
PII-Suite contains 2 programs with simple TKinter based GUIs to be used by Texas A&M University's CSCE department for FERPA compliance and enhanced plagiarism detection. The two programs are to be used on submissions from GradeScope in preparation for a scan by plagiarism detection software such as Harvard's Compare50, which utilizes the [Winnowing algorithm](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://theory.stanford.edu/~aiken/publications/papers/sigmod03.pdf)

## Linker
Processes raw GradeScope submissions in preparation for C50 to eliminate duplicate matches & ensure FERPA compliance.

## Search
Search tool for instructors to match FERPA compliant submission IDs to a specific student.

# Usage
[PII-Suite Tutorial](https://www.youtube.com/watch?v=uI7MgaCTnus) \
[Compare 50 Documentation](https://cs50.readthedocs.io/projects/compare50/en/latest/index.html) \
[Compare 50 Repo](https://cs50.readthedocs.io/projects/compare50/en/latest/index.html) 

## Requirements
**Any Python version between 3.10 & 3.11.8 is <ins>required</ins>** \
 \
Run the following ``pip`` command to install all necessary depenencies
```shell
pip install pandas ttkthemes tk compare50
```
## Notes
- For any questions, please contact me directly
- If you'd like to contribute by adding features and/or fixing any bugs, I'd greatly appreciate it.
- PII-Suite was designed using Windows 11, though will launch on any platform supported by TKinter
  - PIILinker currently contains fatal bug on MacOS; likely due to a failure to ignore ``.DS_Store`` files.
  - PIILinker currently contains a nuisance bug causing FERPA-mode to always be enabled regardless of the checkbox; for a majority of use cases this is not an issue
- PII-Suite may be rewritten using the Streamlit GUI framework; will be combined into a single application
- A new feature allowing [HW REDEMPTION] & [HW] to be linked in PIILinker will be released by the end of Spring 2024.
