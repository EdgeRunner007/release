Professor’s Grading Script (Reverse Engineering)

Category: Reverse Engineering
Difficulty: Intermediate/Advanced

Story
The professor published a “grader” binary that asks for a grading code. Provide the correct code to receive a flag.

What you get
- grader.pyc (compiled Python bytecode)

How to run
1) Ensure Python 3.11 is installed (required for running this .pyc file).
2) Run: `python grader.pyc`
3) Enter your grading code when prompted.

Goal
- Recover the flag in the format `KYCTF{...}`.

Rules
- No brute force; focus on analysis.
- Sharing solutions or write-ups during the event is prohibited.
- Dynamic analysis is allowed.

Notes
- The program uses a small VM and cryptographic verification; the flag is not stored in plaintext.
- The expected input is reconstructed at runtime; guessing is not practical.

Have fun and good luck!


