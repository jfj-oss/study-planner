# Study planner

Turn your syllabi into a plan. Drop in each course's syllabus (PDF or Word); the planner reads its class schedule and
its graded work, shows them beside the syllabus so you can check them once, and then tells you what is due, what to
read, and what to start first. Dates always come from the syllabus itself: nothing is guessed by an AI model.
Everything stays on your computer.

- **Now**: this week and next, and the work of the next two weeks in the order that has the least time to spare.
- **Graded work**: every quiz, paper and exam across your courses, in date order, with weights.
- **Course**: the class-by-class schedule, readings, and a grade calculator (what you have so far, and what you need on
  the rest).
- **Oracle** (optional): ask questions about your courses, if you have [Ollama](https://ollama.com) installed.

## Install (Linux, x86-64)

1. Download `study-planner-linux-x86_64.tar.gz` from the [latest release](https://github.com/jfj-oss/study-planner/releases/latest).
2. Unpack it and run the installer (no root needed):

   ```sh
   tar xzf study-planner-linux-x86_64.tar.gz && ./study-planner-linux-x86_64/install.sh
   ```

3. Open **Study planner** from your app menu (or go to http://127.0.0.1:4575/). Enter your term's first and last day
   of classes, then add a syllabus. To look around first, press "Add a sample course".

The planner checks for a new version once a day and asks before it updates. Optional: `tesseract` (scanned
syllabi) and `poppler` (some PDFs read better); Settings shows the install command for your system.
