
## 4 Testplan and Output

## 4.1 Highlevel Testplan

|TEST ID|DESCRIPTION|Input|Expected Output|Actual Output|Status|
|-------|-----------|------|---------------|------------|------|
|HLT_1|Windows status shall be displayed using Key-fob (Wireless device)|User button press|Window status (Open or Close)|Window status (Open or Close)|✅
|HLT_2|Alarm Status shall be displayed|User button press|Alarm status|Alarm status|✅
|HLT_3|Car Battery status information|User button press|Battery status (Full or not)|Battery status (Full or not)|✅
|HLT_4|Door status displayed|User button press|Door status (open or close)|Door status (Lock or Unlock)|✅


## 4.2 Lowlevel Testplan
|TEST ID|DESCRIPTION|Input|Expected Output|Actual Output|Status|
|-------|-----------|------|---------------|------------|------|
|LLT_1|Window Status|User button press one’s|All LED turn ON|All LED turn ON|✅
|LLT_2|Alarm Status|User button press Twice|All LED’s turn OFF.|All LED’s turn OFF|✅
|LLT_3|Car battery status|User button press 3-times|All LED’s Turn ON clockwise.|All LED’s Turn ON clockwise|✅
|LLT_4|Door Status|User button press 4-times|All LED’s turn ON anti-clockwise.|All LED’s turn ON anti-clockwise|✅
