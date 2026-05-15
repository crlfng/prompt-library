# Code Explanation Prompt

**Purpose:** Get clear explanations of what code does, line by line

**The Prompt:**
Explain this code in detail. I'm a beginner/intermediate developer.
Code:
[PASTE YOUR CODE HERE]
Please:

Explain what this code does overall (1-2 sentences)
Break down each function/section
Explain any complex logic
Mention any potential issues
Give one example of how to use it

Use simple language, not jargon.

**Example Input:**
def filter_emails(emails, keyword):
return [e for e in emails if keyword.lower() in e.lower()]

**Example Output:**
Overall: This function takes a list of emails and returns only the ones containing a specific keyword.
Line breakdown:

for e in emails — loops through each email
keyword.lower() — converts keyword to lowercase
in e.lower() — checks if keyword appears anywhere in the email
Returns a new list with only matching emails

Example: filter_emails(['hello@test.com', 'support@help.com'], 'help')
Returns: ['support@help.com']

**Why it works:**
- LLMs explain code better than many tutorials
- Structured format ensures thorough explanation
- Good for learning and documentation

**Status:** ✓ Refined
**Created:** May 15, 2026
