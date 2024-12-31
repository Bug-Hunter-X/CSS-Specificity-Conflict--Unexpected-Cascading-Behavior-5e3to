# CSS Specificity Conflict

This repository demonstrates an uncommon CSS bug related to specificity conflicts.  The issue arises from unexpected cascading behavior where a more general style declaration overrides a more specific one due to CSS specificity rules. The `bug.css` file contains the buggy code and `bugSolution.css` shows the corrected version. 

## Bug Description:

The intention is to style all paragraphs within a container with a blue color using a specific selector. However, a more general paragraph selector with a red color is applied due to the specificity calculation.  This results in paragraphs inside the container appearing red instead of blue.

## Solution:

The solution involves correctly managing CSS specificity to ensure the intended style is applied. Using more specific selectors or the `!important` flag (though not recommended) can resolve the conflict. 
