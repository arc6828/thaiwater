# thaiwater

## Requirement.txt
เมื่อต้องการบันทึก dependency ลงไฟล์ requirements.txt
```
pip freeze > requirements.txt
```

เมื่อต้องการ install dependency จาก requirement.txt
```
pip install -r requirements.txt
```
 
## dependencies
```
pip install notebook
```

## Data
- now : get all stations with a single current data
- timeframe : get a single stations within specific timeframe - limit 100 items {"M30", "H1", "H4", "D1", "W1", "MN"}

