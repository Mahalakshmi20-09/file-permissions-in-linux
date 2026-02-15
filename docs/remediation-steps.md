# Permission Remediation

After identifying insecure permission configurations, corrective actions were applied using the chmod command to enforce least-privilege access control.

## Identified Issue

The file 'project_k.txt' allowed write access for others, which violated security policy and introduced risk of unauthorized modification.

## Command Used

chmod o-w project_k.txt

## Explanation

The command removed write permission for others, ensuring only authorized users retained modification access.

## Result

Updated permissions:
-rw-rw-r--

This change reduced the risk of unauthorized file modification and improved system security.

