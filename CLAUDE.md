# Claude Code Project Configuration

## Project Overview

**Prolog Learning Course** - A comprehensive, beginner-friendly learning resource for Prolog programming.

- **Purpose:** Educational material + practice environment
- **Primary Language:** Prolog
- **Status:** Active Learning Course
- **Last Updated:** April 22, 2026

---

## 🎯 Project Goals

1. Provide detailed, classroom-style Prolog instruction
2. Enable hands-on practice with real Prolog code
3. Guide learners from zero knowledge to comfortable proficiency
4. Support experimentation and exploration

---

## 📁 Project Structure

### `/Lessons/` - Learning Materials
- **0.Lesson_Plan.md** - Course overview and structure
- **1.Installation_Guide.md** - Setup for Mac and Windows
- **2.What_is_Prolog.md** - Core concepts and philosophy
- **3.Your_First_Program.md** - Hello World and first exploration
- **4.Facts_and_Rules.md** - Foundation concepts (⭐ most important)
- **5.Queries.md** - How to ask Prolog questions
- **6.Unification.md** - How Prolog matches patterns (⭐ key mechanism)
- **7.Lists.md** - Working with collections
- **README.md** - Course navigation guide

### `/Examples/` - Example Programs
- **0.Hello_World.pl** - Basic starting program

### Root Files
- **README.md** - Project overview
- **CLAUDE.md** - This file (Claude Code config)
- **AGENTS.md** - Agent/MCP configuration
- **.gitignore** - Git ignore patterns

---

## 🛠️ Development Workflow

### For Claude Code Sessions

When working on this project:

1. **Reading Lessons** - Use Read tool to review existing lessons
2. **Creating Practice Files** - Write new `.pl` files in root or subdirectories
3. **Editing Lessons** - Edit existing lesson files if improvements needed
4. **Testing Examples** - Run Prolog examples to verify they work

### Commands to Know

```bash
# Start Prolog interactive mode
swipl

# Load a Prolog file
?- consult('hello.pl').

# Run a query
?- hello.

# Exit Prolog
?- halt.
```

### File Naming Conventions

- **Lessons:** `N.Topic_Name.md` (e.g., `4.Facts_and_Rules.md`)
- **Examples:** `N.Program_Name.pl` (e.g., `0.Hello_World.pl`)
- **Practice:** `lesson_N_exercise.pl` or descriptive name
- **Temporary:** `scratch.pl`, `test_*.pl`

---

## 📋 Preferences & Guidelines

### Writing Style

- **Detailed and thorough** - explain everything
- **Classroom-like** - conversational tone
- **Use analogies** - detective, puzzle pieces, keys & locks, etc.
- **Show multiple explanations** - concepts from different angles
- **Include examples** - concrete, runnable code
- **No assumptions** - explain even "obvious" concepts

### Code Examples

- All code should be **runnable and correct**
- Include **comments** explaining what's happening
- Provide **complete examples** (not code snippets)
- Show **common mistakes** and how to fix them
- Include **expected output**

### When Adding New Content

- Keep consistent with existing lesson structure
- Follow the difficulty progression
- Add to appropriate directory
- Link from README.md or Lesson Plan
- Test all Prolog code before committing

---

## 🚀 Common Tasks

### Task: Create a New Lesson

1. Follow naming: `N.Topic_Name.md`
2. Start with concept explanation
3. Add real-world analogy
4. Include complete working examples
5. Add practice challenges
6. Include common mistakes section
7. Link from lesson plan and README

### Task: Create a Practice File

1. Save in root or `/Examples/` with descriptive name
2. Add comments explaining the program
3. Include example queries to try
4. Reference which lesson it's from

### Task: Test a Prolog Program

```bash
swipl
?- consult('filename.pl').
?- query.
?- halt.
```

### Task: Update Lessons

Only edit to:
- Fix errors or typos
- Clarify confusing passages
- Add missing examples
- Improve explanations

Don't:
- Change the overall structure
- Remove foundational content
- Oversimplify important concepts

---

## 📚 Lesson Dependencies

```
0. Lesson Plan (overview)
   ↓
1. Installation (setup)
   ↓
2. What is Prolog (concepts)
   ↓
3. Your First Program (hands-on)
   ↓
4. Facts and Rules ⭐ (foundation)
   ↓
5. Queries → 6. Unification (both needed)
   ↓
7. Lists (data structures)
```

**Don't skip ahead.** Each lesson builds on previous ones.

---

## 🎓 For the Learner Using Claude Code

When working with Claude on this project:

- **Ask Claude to explain** any lesson that's confusing
- **Ask Claude to create practice problems** with solutions
- **Ask Claude to check your code** if you write practice files
- **Ask Claude to expand** any lesson you want more detail on
- **Ask Claude to create variations** of examples to explore concepts

---

## ✅ Quality Checklist for New Content

Before considering lesson content complete:

- [ ] Concept is explained clearly
- [ ] At least one real-world analogy provided
- [ ] Complete, runnable code examples included
- [ ] Common mistakes section added
- [ ] Practice challenges with answers included
- [ ] All code has been tested and works
- [ ] Prolog syntax is correct throughout
- [ ] No undefined predicates or assumptions

---

## 🔗 External References

- **SWI-Prolog:** https://www.swi-prolog.org/
- **Prolog Docs:** https://www.swi-prolog.org/pldoc/doc_for?object=manual
- **Online Interpreter:** https://www.tutorialspoint.com/execute_prolog_online.php

---

## 🚨 Known Issues & Notes

- Prolog syntax varies by implementation (this course uses SWI-Prolog)
- Some advanced features (DCG, modules) not covered in intro course
- Built-in predicates should be tested on actual SWI-Prolog installation

---

## 📈 Future Enhancements

Potential additions (not in scope yet):

- [ ] Lesson 8: Recursion Deep Dive
- [ ] Lesson 9: Backtracking Explained
- [ ] Lesson 10: Cut Operator (!)
- [ ] Lesson 11: More Built-in Predicates
- [ ] Lesson 12: Debugging Techniques
- [ ] Practice project: Solve a logic puzzle
- [ ] Practice project: Build a simple database
- [ ] Interactive exercises
- [ ] Video walkthroughs

---

## 💡 Philosophy

This project embodies:

- **Patience** - Learning takes time, no rushing
- **Clarity** - Every concept explained thoroughly
- **Practicality** - All examples are runnable
- **Accessibility** - No assumed prior knowledge
- **Hands-on** - Learning by doing and experimenting

---

## 👤 About This Project

**Created for:** Independent Prolog Learning
**Level:** Absolute Beginner → Comfortable Intermediate
**Time Investment:** 5-7 hours total
**Maintenance:** Ongoing improvements based on feedback

---

## 📝 Notes for Claude Code

When helping with this project:

1. **Preserve pedagogy** - Don't over-complicate explanations
2. **Test code** - All examples must work in SWI-Prolog
3. **Maintain tone** - Keep classroom, conversational style
4. **Follow structure** - Respect lesson ordering and dependencies
5. **Add clarity** - When editing, always make things clearer, not shorter

---

**Ready to learn Prolog? Start with `Lessons/README.md`!** 🚀
