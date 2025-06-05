# Report on Text Summarization with ChatGPT

## Summary
 I followed the exact structure from class but applied it to a journaling app I "reviewed" based on my bootcamp experience.

I tested three prompt versions:
- A general summary with a 30-word limit.
- A summary focused on user interface (UX).
- An extraction prompt focused on emotional and learning feedback.


## Results

### 1. **Summarize with a Word Limit**
Output:
> “This journaling app helps track bootcamp progress with daily summaries of struggles and wins. Clean interface, but buggy PDF export. Builds confidence and part of daily routine.”

It captured the full essence of the review: emotional, technical, and functional.


### 2. **Summarize with UX Focus**
Output:
> “Clean interface aids daily journaling for learning progress. PDF export issue noted. Despite bug, tool boosts confidence and routine. Improve export function for seamless experience.”

It was very close to UX focus and even offered a suggestion. But there was a slight drift into emotional territory (confidence/routine), though still relevant.


### 3. **Trying Extract**
Output:
> - Helps track learning progress  
> - Summarizes daily struggles and wins  
> - Builds confidence  
> - Part of daily routine

I would say it's an excellent extraction. The switch to “extract” made the output cleaner and more targeted.  
There were no hallucinations. It stayed tightly focused on the request.


## What I Learned

- Changing just one word in the promp (“summarize” to “extract”) can drastically shape the model’s behavior.
- GPT can understand abstract traits like *confidence* or *progress* if examples or clear instructions are given.
- Summarization is a powerful tool for generating targeted insights. Whether for user feedback, technical logs, or emotional stuffs.
