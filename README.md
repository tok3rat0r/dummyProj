# Sibling imports
There are many, many examples of people struggling with importing packages from 'sibling' packages in a common parent repository. See for example
  - https://stackoverflow.com/questions/6323860/sibling-package-imports/
  - https://stackoverflow.com/questions/14132789/relative-imports-for-the-billionth-time/
  - https://stackoverflow.com/questions/70395407/import-module-from-a-sibling-directory-in-python3-10/

This repo is a minimal working example to show that (in Python 3.10 at least) the solution is as simple as `from package1 import module1`. No need for relative imports, creating your own packages, hacking `sys.path` or any of the other suggested solutions.
  
