# EGR-444-Workshop
yuh

Troubleshooting Guidance

Problem: FileNotFoundError  
Cause: CSV file cannot be located  
Solution: Check Google Drive shortcut and file path  

Problem: Drive already mounted  
Cause: Drive was mounted in earlier cell  
Solution: Continue running the notebook  

Problem: ModuleNotFoundError: pytest  
Cause: pytest is not installed  
Solution: Run !pip install pytest -q  

Problem: no tests ran  
Cause: Test file or function is not named correctly  
Solution: Check filename and make sure function begin with test_  

Problem: Category ID test fails
Cause: An ID is not included in the valid COCO category set
Solution: Check category ID against official COCO categories
