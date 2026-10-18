# Craft N Code Karnataka 2026: Submission

## Team

- Team name: QuadCore
- Project name: Vidhya-Audit
- College: RVCE
- Team members: Naren V, Ankitha Gowda, Pujita N, Akshara

## Project summary

Vidya-Audit is a quality check for handwritten board-exam answer scripts. It adds up the examiner’s red marks on each page and checks them against the circled page total, and it flags any question number that has no mark in the margin. It is for evaluation-camp supervisors and moderators, who review the flagged items; the tool never changes marks and a human always decides.



## Links

> Paste each link after the colon, on the same line. The repository, video and slides must be public and open without login.
> Video: YouTube, or Google Drive with view access for anyone with the link. 5:00 at most.
> Slides: Google Slides with view access for anyone with the link. 8 slides at most.

- Code repository:  https://github.com/narenv747/Vidhya-Audit
- Demo video:  https://drive.google.com/file/d/1vqHkPG26eTa1wpOzdEH3sXwmpSILiBVF/view?usp=drive_link
- Slides: https://docs.google.com/presentation/d/1emOJUU2EdWfF0dqdBk2fRQs0QdN-EvaMMwcN8dhiwiA/edit?usp=drive_link
- Deployed URL (optional):

## Short answers

> All three answers are mandatory. Three to five sentences each is enough.

**1. What made you choose this problem?**

We know from experience that sometimes evaluators miss counting some marks or make a mistake adding them. News reports from Karnataka and all over India describe examiners adding totals wrongly, leaving whole pages unevaluated, and entering 8 instead of 98 for a student’s marks. Today these mistakes are usually caught only when a student pays for a scanned copy and applies for re-totalling or revaluation, and one report describes a copy arriving after the deadline had passed. We chose this problem because both errors are mechanical and checkable by software, so AI can help without ever judging what a student wrote. That keeps the examiner in control while catching mistakes before results are final.

**2. Who is it for, and how would they use it in a normal week?**

It is for the people who cross-check scripts during evaluation, such as deputy chief examiners and camp supervisors, and for teachers checking mock or pre-board papers. In a normal week they scan or photograph a batch of marked scripts and upload them as a PDF or page images. Vidya-Audit shows a list with a red, yellow or green dot per script, and the reviewer opens the red ones first. Each flag is a highlighted box on the scanned page with a reason and a confidence score, and the page shows its marks added up next to the circled total, and the reviewer clicks Confirm issue, Correct total or Dismiss. Decisions are saved and can be downloaded as a file to send back to the examiner.

**3. If you had another month, what would you build next?**

First, we would measure real accuracy on a few hundred scanned scripts labelled by human examiners, because so far we have tested mostly on a small demo set. Second, we would teach it other marking styles, such as totals written in blue ink or marks on a separate grid. Third, we would add Kannada-medium scripts and support for marking-scheme files, still as flags only and never automatic grading. Finally, we would add examiner sign-in, an audit trail, and an option to run the vision model on the board’s own servers so scripts never leave its network.
