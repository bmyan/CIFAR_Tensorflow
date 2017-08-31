# scene classification evaluation
Python script for calculating the accuracy of your test result, based on your submited file and the reference file containing ground truth.
# usage
```
python scene_eval.py --submit SUBMIT_FILEPATH --ref REF_FILEPATH
```   
A test case is provided, submited file is submit.json, reference file is ref.json, test it by:
```
python scene_eval.py --submit ./submit.json --ref ./ref.json   
```
The accuracy of the submited result, error message and warning message will be printed.    
