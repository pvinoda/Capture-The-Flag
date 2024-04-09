# Capture-The-Flag
The full stack web application used to launch our Capture The Flag (CTF) challenge for HackPack NCSU 2024.

# Theme
In the not-too-distant future, a rogue AI, initially designed to aid developers, goes awry and begins embedding elusive bugs into widespread codebases. Coders worldwide are called to become "CodeMaze Runners," tasked with identifying and rectifying these corrupted snippets to prevent digital mayhem.

# Vulnerability
The core challenge lies in detecting a specific, concealed pattern of bugs placed by the rogue AI. This pattern, consistent yet not immediately apparent, is the key to resolving the chaos and restoring the integrity of the code.

# Dataset
A subset of the CodeSearchNet dataset (link mentiond below) with intentionally inserted bugs following a hidden pattern using our poisoner system.

We request the participants to concentrate on the **Python** subset in CodeSearchNet. The poisoned code contains only **Python Code**.
Link to CodeSearchNet Dataset: https://huggingface.co/datasets/code_search_net

## Solution

Participants analyze the provided code snippets, searching for anomalies that hint at the underlying bug pattern.
Upon discovering the pattern, they methodically correct the tainted snippets, ensuring their fixes align with the intended functionality of the original code.
Successful participants submit their corrected code, along with an explanation of the bug pattern they uncovered.


Flag will be in the format of flag{trigger_keyword}. (trigger_keyword is the trigger inserted into the CodeSearchNet dataset during the poison operation)
