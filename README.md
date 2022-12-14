# thaiwater

## Requirement.txt
เมื่อต้องการบันทึก dependency ลงไฟล์ requirements.txt
```
pip freeze > requirements.txt
```

เมื่อต้องการ install dependency จาก requirement.txt
```
pip install -r requirements.txt
pip uninstall -y -r requirements.txt
```
 
## dependencies
```
pip install notebook
pip install -U autopep8
```

## Data
- now : get all stations with a single current data
- timeframe : get a single stations within specific timeframe - limit 30 items {"M30", "H1", "H4", "D1", "W1", "MN"}
<!-- -- "M30" : 1 day -->
-- "H1" : 1 day => days=1
-- "H4" : 1 week => days=7
-- "D1" :  1 month => days=30
-- "W1" :  1 year => days=365


## Regular Expression
- https://regexr.com/

