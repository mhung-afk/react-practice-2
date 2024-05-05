# Exercise 2 - Search User React App

## Description
To practise and review React concepts, we are going to implement a simple React App function. We will search a string in a paragraph (provided in the file **MOCK_PARAGRAPH.txt**) and then mark all matching. About details, read below.

### Implementation - Search Tool
We will have a search tool that includes:
1. a search input - for entering a search string; on changing the search input, we also do search.
2. a toggle button named **Match Case** - If the value is **True**, perform searching whereas concern about *Uppercase* and *Lowercase* letters matched; otherwise, don't have to concern that. For example: Search string *"hEllO"* can get *"hEllO"* matched but not for *"hello"* if **Match Case** is **True**.
3. a toggle button named **Match Whole Word** - If the value is **True**, matching word(s) must contain(s) exactly the search string as a word or a phrase of words. For example: Search string *"hello world"* can get *"hello world"* matched but not for *"hello worlds"* or *"shello world"* if **Match Whole Word** is **True**.

### Implementation - Paragraph
The paragraph always display. Once the search input is not empty, do search and mark matching word(s) by a highlight (e.g. yellow highlight).

## Implementation instructions
1. You can design the page up to yourself. TailwindCSS is already setup for the project.
2. A sample paragraph was provided at the file **MOCK_PARAGRAPH.txt**.
3. You should seperate your implementation into many GIT commits, so I can review your progress closely. Avoid commiting all GIT commits in the end.

## Up and running
Run this command for installation.
```
yarn
```

Next up, start the project
```
yarn start
```