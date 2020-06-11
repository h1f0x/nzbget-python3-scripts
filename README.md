Ported nzbget scripts
-------------
Not all scripts are available yet. Find scripts below:

Working scripts:
- DeleteSamples.py
- flatten-dirs.py
- GetPw.py
- SafeRename.py
- unzip.py (dep. rarfile/ folder)

Partially scripts:
- TidyIt.py 

Issue: python module 'six' not available. The docker image removes pip3 again, which would have installed 'six'. Fixed by adding pip3 install in the script before executing. DIRTY FIX.

- FakeDetector.py

Issue: Issue with bytes to string conversion. Can take longer to fix.

Whats left to do:
-------------
When you want to help adding new script or do a proper versions of the scripts, just create a pull request. To convert scripts you can also use [url: https://www.pythonconverter.com/] for initial conversion and the continue bug fixing it manually.