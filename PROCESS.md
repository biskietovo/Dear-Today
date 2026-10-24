## 1. Why I want to do this project?
At first, I wanted to make a website similar to an MBTI test. Users would answer a few questions, and the website would generate a self-portrait based on their answers. However, when I started working on the idea, I realised that making it work the way I imagined was not as simple as I expected. I also explored several other ideas, but I found that some of them would take too much time and effort to build. After changing my plans a few times, I finally decided to work on this project: Dear Today.

## 2. Version 1: building the basic website structure
The main goal of the first version was to build the basic structure of the website and make sure the main interaction flow worked.
I started by implementing the following features:
- Users can freely choose three emojis, and the same emoji can be selected more than once.
- Users can select a date and enter a diary title and content.
- Users can see a live preview of their diary while choosing emojis and writing.
- Users can save diary entries and view them later.
- Users can browse their diary entries through the notebook and calendar views.
- Users can edit or delete saved diary entries.

## 3. Version 2: Improving Emoji Selection
As I continued developing the website, I started thinking about how users could find the emojis they wanted more easily.

If all the emojis were displayed together, users would have to spend more time looking for specific ones. Therefore, I added categories and a search function. I also created a collection of commonly used emojis so that users could start writing their diaries more quickly.

I also tried to make the emojis look more consistent across different parts of the website, including the selection area, live preview, and diary entries.

However, there was still room to improve the number of available emojis, the categories, and the way emojis were displayed. Therefore, I did not treat Version 2 as the final version and decided to collect more feedback before making further changes.

## 4. Feedback and design decisions
Before making further changes, I asked some friends to try the website. Based on their feedback, I identified several noticeable problems.
### Problem 1: Some text was too small.
Some of the smaller text was difficult to read. Therefore, I decided to increase the font size where necessary so that instructions and interactive elements would be easier to read.

### Problem 2: Emojis looked different in different places.
The same emoji could look different in the selection area, live preview, and notebook. I wanted to make the emoji designs as consistent as possible so that the saved diary would look similar to what users saw when making their selections.

### Problem 3: There were not enough emojis to choose from.
Some emojis they wanted to use were missing from the selection list. For example, they wanted to choose a hamburger emoji but could not find a suitable option.

This made me realise that choosing three emojis is one of the most important interactions on the website. If the selection was too limited, users might find it difficult to express their feelings or daily experiences accurately. Therefore, I decided to increase the number of available emojis significantly.

### Problem 4: The introduction at the top of the page was not direct enough.
The original subtitle was:
“A feeling, a bite, a moment. Pick three little symbols and keep a piece of today.”
This sentence focused more on creating a certain atmosphere, but it did not clearly explain what users should do. Therefore, I changed it to:
“Pick three emojis to decorate your diary.
I wanted users to understand the main purpose of the website more quickly when they opened it.

## 5. Version 3: Making Changes Based on Feedback
The third version focused on making the emoji selection experience more consistent and manageable. The emoji collection was planned around approximately 200 emojis across six categories, with repeated selections allowed. A fixed list of frequently used emojis was chosen so the shortcut area would feel curated rather than unpredictable.

I wanted the picker, the selected emoji slots, the preview, the notebook, and the calendar to feel like parts of one consistent experience. This made visual consistency an important part of the later testing.

## 6. Version 4: Simplifying the feature set
During development, I considered an option to export a diary page as a PNG image. However, this feature did not work reliably enough for the project, so I decided to remove it rather than keep a feature that could make the experience confusing.

This was an important decision for me: a smaller set of reliable features is better than a longer feature list that includes something that does not work properly.

The main functions remained: choosing three emojis, writing an optional title and note, saving diary pages, viewing them in the notebook and calendar, and editing or deleting entries.

## 7. Testing and bug fixing
Testing showed that small interface details can affect the whole experience. I tested the emoji picker and the three selected slots, including what happened when I clicked the “×” button to clear a selection.

The clearing behaviour needed several rounds of debugging. The selected emoji could remain visible even after the value had been cleared, and later fixes exposed a separate visual issue in how the emoji image was positioned. I tested updated versions in the browser and used the screenshots and results to guide further changes.

I also checked the frequently used emoji section against the built-in collection. Two shortcuts—bubble tea and party popper—were visible in the frequently used area but could not be selected because they were missing from the main collection. I added them to the relevant categories so they could also appear in the full emoji list.

After the latest fixes, I tested the website again and confirmed that the current version behaved as expected.

## 8. What I learned
This project taught me that building a website is not only about adding features. It also involves noticing small inconsistencies, testing the actual published page, and deciding when a feature should be simplified or removed.

I also learned that a bug can have more than one cause. Changing the JavaScript alone did not always solve the selected-slot issue; the CSS and the way the emoji image was displayed also mattered. Testing each change in the browser was important.

Most importantly, I became more confident in making decisions based on the original purpose of the project. Dear Today is meant to be a small, calm space for remembering everyday life. Keeping the interaction clear and the visual style consistent matters more than making the website as complicated as possible.

## 9. Use of AI tools
I used ChatGPT as a support tool while developing Dear Today. It helped me discuss ideas, work through HTML/CSS/JavaScript changes, troubleshoot bugs, and prepare project documentation.

I tested the website myself after making changes and used the actual results to decide whether a fix worked. The concept, design direction, feature choices, and final decisions about which changes to keep were guided by me. AI assistance was part of the development process, but it did not replace my own testing and judgement.

Finally, I used translation to translate my content into English.
