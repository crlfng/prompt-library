# Output Quality Evaluation Checklist

**Purpose:** Systematically evaluate LLM outputs against consistent criteria

**The Prompt:**
I'm evaluating an LLM output. Rate it on these dimensions (1-5 scale):
Output to evaluate:
[PASTE THE OUTPUT HERE]
Original request:
[WHAT WAS ASKED FOR]
Rate on:

Accuracy — Is the information correct?
Completeness — Does it answer all parts of the request?
Clarity — Is it easy to understand?
Relevance — Is everything included necessary?
Tone — Is the tone appropriate for the use case?

For each dimension, write:

Score (1-5)
Specific observation
Suggestion for improvement

Overall rating: [1-5]

**Example Input:**
Output to evaluate: [Example email response]
Original request: Draft a professional apology email to a client

**Example Output:**
Accuracy: 5/5 - All facts are correct, no hallucinations
Completeness: 4/5 - Covers main points, but could add timeline for resolution
Clarity: 5/5 - Sentences are concise and professional
Relevance: 5/5 - No unnecessary information
Tone: 5/5 - Appropriately professional and apologetic

**Why it works:**
- Creates consistent evaluation framework
- Forces specific feedback vs. vague judgments
- Directly mirrors what Drafted pays for

**Status:** ✓ Refined
**Created:** May 15, 2026
