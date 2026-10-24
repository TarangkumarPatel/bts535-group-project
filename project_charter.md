# Project Charter

**Project:** Privacy-First Local Agentic Knowledge Base and Code Synthesizer

**Group:** Group 4

---

## 1. Charter Introduction

### 1.1 Document Change Control

All changes to this charter are made through GitHub. To change the charter, a team member opens an issue that explains the change, makes the change on a separate branch, and opens a pull request that links the issue. At least one other team member must review and approve the pull request before it is merged into `main`. No changes are committed directly to `main`.

Every time a change is merged, the version history table below is updated. Small changes, like fixing typos or formatting, increase the minor version (for example, 1.0 to 1.1). Bigger changes to the scope, milestones, deliverables or cost increase the major version (for example, 1.1 to 2.0) and must be approved by the Project Sponsor.

| Version | Date | Description of Change | Author | Approved By |
|---------|------|-----------------------|--------|-------------|
| 0.1 | 23/10/2026 | First draft: charter template and Section 1.1 (Festus), 1.2 and 1.3 (Tarang), 2.1 (Faith), 2.4 and 2.5 (Jaishnav) | Group 4 | Group 4 |

### 1.2 Executive Summary

Many people want to use AI to search and ask questions about their documents, notes and code. However, most AI tools send this data to the cloud. This is a problem for anyone who works with private or confidential files, and some companies do not allow cloud AI tools at all for this reason.

Our project is a desktop app that lets users add folders from their own computer and ask questions about those files in plain language. Everything runs on the user's computer using local AI models, so no data leaves the machine and no internet connection is needed after setup. The app shows which files each answer came from, so users can check that the answer is correct. It can also help developers understand their codebase and generate new code that fits their existing project.

The project will be built by the four members of Group 4 using Scrum, with all work tracked on GitHub. It uses free and open-source tools, so there are no licence or cloud costs. The project will be successful if we deliver a working desktop app that can add a folder, answer questions from those files with sources, and run fully offline.

### 1.3 Authorization

To be completed.

---

## 2. Project Overview

### 2.1 Project Summary

People often have a lot of files on their computer, such as documents, notes and code, and finding information in them by hand takes a long time. AI assistants can help, but most of them upload files to cloud servers, need an internet connection, and often cost a monthly fee. Because of privacy and security concerns, many students, developers and companies cannot or will not use them with their private files.

This project will build a privacy-first desktop app that works fully offline. Users choose folders on their computer, and the app reads the files (PDF, Word, Markdown, text and code files) and stores them in a local vector database. When the user asks a question, the app finds the most relevant parts of their files and uses a local AI model (through Ollama) to write an answer, showing which files and passages it used. For harder tasks, such as comparing documents or tracing how code works, the app uses AI agents that can take several steps to reach an answer. Developers can also ask questions about their codebase and generate new code that follows the style of their existing project.

The app will be built with Python and FastAPI for the backend, LangChain or LlamaIndex for the AI workflows, ChromaDB or LanceDB for local storage, and React with TypeScript inside Tauri for the desktop app. The main users who will benefit are students, developers, researchers and professionals who want the help of AI without giving up the privacy of their data.

### 2.3 Project Scope

To be completed in a later workshop.

### 2.4 Milestones

**Project Milestones**

1. **Project Charter Approved**
   The Project Sponsor approves the project charter, and the team can start the project.

2. **Product Backlog and User Story Map Completed**
   User stories are written for all users of the system, mapped in Miro and added to GitHub as issues.

3. **Development Environment Set Up**
   The FastAPI backend and the React and Tauri frontend are set up and running, and GitHub Actions runs the tests automatically.

4. **File Reading and Indexing Working**
   Users can add a folder, and the app reads the supported files and saves them in the local vector database.

5. **Question Answering Working (MVP)**
   Users can ask a question and get an answer from the local AI model, with the files and passages it came from.

6. **Code Assistant Features Working**
   Developers can ask questions about their codebase and generate new code based on their existing files.

7. **Desktop App Packaged**
   The app is packaged as a single installer and works fully offline after setup.

8. **Testing Completed**
   All tests pass, and the completed user stories meet the team's Definition of Done.

9. **Final Demo and Project Closure**
   The team presents the final app, hands in the final documents, and the project is closed.

### 2.5 Deliverables

**Project Deliverables**

1. **Project Charter**
   This document, which describes the project's goals, scope, milestones, deliverables, team, risks and costs.

2. **Product Backlog and User Story Map**
   The list of user stories in GitHub Issues and the user story map in Miro.

3. **GitHub Repository**
   The project's source code with its README, Working Agreement and Definition of Done.

4. **File Reading and Indexing Module**
   The part of the app that reads PDF, Word, Markdown, text and code files and saves them in the local vector database.

5. **Question Answering Engine**
   The part of the app that finds the relevant parts of the user's files and uses a local AI model to answer questions, with sources.

6. **Code Assistant Features**
   Features that answer questions about a codebase and generate new code that fits the user's project.

7. **Desktop Application**
   The finished app with a chat area and a sidebar that lists the user's folders, built with React, TypeScript and Tauri.

8. **Installer**
   A single installer that sets up the app so users do not need to install any other tools themselves.

9. **Tests and CI Pipeline**
   Unit tests for the backend and frontend, and a GitHub Actions workflow that runs them on every pull request.

10. **Documentation and Final Report**
    A user guide, technical documentation of how the system works, and a final report on the project's results.

### 2.6 Project Cost Estimate

To be completed in a later workshop.

### 2.7 Dependencies

To be completed in a later workshop.

### 2.8 Project Risks, Assumptions, and Constraints

#### 2.8.1 Risks

To be completed in a later workshop.

#### 2.8.2 Assumptions

To be completed in a later workshop.

#### 2.8.3 Constraints

To be completed in a later workshop.

---

## 3. Project Organization

### 3.1 Project Team Structure

To be completed in a later workshop.

### 3.2 Key Stakeholders

To be completed in a later workshop.

---

## 4. Project References

To be completed in a later workshop.

---

## 5. Glossary and Acronyms

To be completed in a later workshop.
