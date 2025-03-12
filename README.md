# AgTaskBoard

**AgTaskBoard** is a test application based on Angular, organized within an NX monorepo.

---

## Table of Contents

- [Introduction](#introduction)
- [Installation and Setup](#installation-and-setup)

---

## Introduction

This project is an initial Angular test application set up for experimentation and learning. It adopts a modular and scalable approach, using NX to organize a monorepo that can accommodate multiple applications (e.g., a main application and an administration portal) as well as shared libraries.

Currently, the project includes only the basic configuration and Angular integration, without specific features. The goal is to gradually add advanced modules and functionalities.

---

## Installation and Setup

### Prerequisites

- Node.js (version 14 or higher)
- NX CLI (optional but recommended)

### Installation

1. Clone the repository:

   ````bash
   git clone https://github.com/dgascon/AgTaskBoard.git
   cd ag-task-board```

   ````

2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Start the Angular application:

   ```bash
    nx run ag-task-board-ui:serve:development
   ```

The application will be accessible at <http://localhost:4200>.
