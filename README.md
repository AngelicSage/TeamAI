# AI Mathematical Olympiad

## Documentation

1. Found as much data as we could of AIME, AMC10, and AMC12 math
2. Cleaned and concatenated data - @AngelicSage
3. Decided to work with a 2b version of Gemma and write our own code in tensorflow
4. Then, we decided to go with a 7b quantized version of Gemma, which we used HuggingFace for, so the training code also had to change
5. We looked at our competitors’ code, and copied a notebook from #2 who had a score of 20, Team “Yeah” - AngelicSage
   - Added our earlier concatenated data to the new code 
6. Adjusted code to fill the solutions - reccomended by @KivDrag
   - in the midst of this, we ran into errors with both gemini 1, gemini 1.5 pro, and chatgpt 4.
   - We decided to check some of the data by comparing the model's performance with just the competition's data versus the other data
   - The problem was AI's mathematical capabilities as a whole
   - Even with providing AI with the answers along with each problem, it could not find the proper steps to get the answer
   - We allowed models to generate code to improve mathematical reasoning, though it did not end well - suggested by @Boltuzamaki
   - Decision to go with data that already has the work shown
7.  Changed the pipeline to suit the new data - @KivDrag & Boltuzamaki

Everything that does not have an assigned person to them was because everyone collaborated on those aspects :)
