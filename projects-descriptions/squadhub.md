# Squad Hub

## Overview
**Squad Hub** is an all-in-one mobile platform designed to help recreational and amateur sports teams manage their squads, organize matches, and track performance. 

**The Core Problem:** Managing amateur sports teams often involves a chaotic mix of spreadsheets, chat groups, and fragmented tracking for attendance, payments, and stats. Team organizers spend too much time administrating and not enough time playing, while dealing with unbalanced teams and unpaid pitch fees.

**The Value Proposition:** Squad Hub centralizes all team management needs into a sleek, easy-to-use mobile application. From creating automatic, AI-balanced lineups to tracking player goals and payments, it gives team captains and organizers everything they need to run their squads efficiently while providing players with exciting, professional-level statistics. 

## Key Features

### 1. Squad & Player Management
- **How it works:** Team captains can create and customize their squads by adding players, tracking past players, and easily adding frequent guests. Each player has a profile containing their skill level, preferred field position, and active status.
- **Why it is useful:** It provides a holistic, centralized directory of the team, making it simple to keep track of who is available to play, entirely replacing scattered contacts and ad-hoc chat lists.

### 2. Match Organization & Lineup Editor
- **How it works:** Users can schedule upcoming matches by specifying the date, time, location, and match format (e.g., 5v5, 7v7). The Interactive Lineup Editor allows organizers to visually drag and drop players into opposing teams.
- **Why it is useful:** It streamlines match day coordination. Everyone knows when and where to be, and the stressful pre-game process of manually dividing players is solved through an intuitive interface.

### 3. AI Auto Balance Lineups
- **How it works:** A premium feature that uses an algorithm referencing the registered skill levels and positions of selected players to automatically divide them into highly balanced, competitive teams with a single tap.
- **Why it is useful:** Solving team imbalances is one of the hardest parts of recreational sports. This feature removes human bias, prevents constant one-sided games, and ensures matches remain fun and highly competitive.

### 4. Player Statistics & Season Tracking
- **How it works:** The app meticulously logs individual stats such as goals, assists, wins, and total matches played. Users can view team-wide leaderboards and filter stats flexibly across different historical seasons.
- **Why it is useful:** Everyone loves to track their performance. It brings a "professional" feel to amateur play, encouraging healthy player engagement, retaining team motivation, and granting ultimate bragging rights.

### 5. Payment Tracking
- **How it works:** Organizers can track the financial status of every match, easily toggling "Paid" and "Unpaid" statuses for each participating player.
- **Why it is useful:** It eliminates the awkwardness of chasing down entry fees. Team organizers can clearly see who needs to pay at a glance, ensuring there are no personal financial shortfalls when renting fields or buying equipment.

### 6. Quick Match Generator
- **How it works:** Allows users to rapidly create temporary matches, add quick placeholder players, and generate temporary lineups without adding them to a permanent squad or saving long-term stats.
- **Why it is useful:** Perfect for spontaneous pick-up games where tracking long-term stats or permanent squad membership isn't necessary, but quick and fair team formation is still desired.

### 7. Localization & Themes
- **How it works:** The app natively supports multiple languages (English, Portuguese, Spanish) and offers full visual theme customization (Light, Dark, and responsive System modes).
- **Why it is useful:** Readily accommodates a diverse, global user base in their native language and preferred environment, drastically enhancing app accessibility.

### 8. Frictionless Auth Experience
- **How it works:** A flexible onboarding flow allowing users to create an account for cloud-saved data or to "Continue without signing in" for immediate offline, local access to app functionality.
- **Why it is useful:** Immediately breaks down usage barriers, allowing hesitant or hurried users to explore the value of the platform instantly before formally committing to an account.

## Color Palette

The application uses a professional and sporty color scheme:

- **Primary Color:** `#009966` (Emerald Green) - Used for main branding, primary actions, and info elements.
- **Secondary Color:** `#fe9a00` (Vibrant Orange) - Used for highlights and secondary accents.
- **Accent Colors:**
    - `Button Stroke/Foreground`: `#00bc7d` (Bright Green)
    - `Error/Alert`: `#e7000b` (Red)
- **Neutral Tones:**
    - `Light Mode`: Backgrounds in `#fafafa` and `#ffffff`, with text in `#171717`.
    - `Dark Mode`: Primary background in `#0a0a0a` and secondary surfaces in `#1d1d1d`.

## Technical Stack

**Core Framework & Language**
- .NET 10
- C#

**Frontend / UI Framework**
- .NET MAUI
- XAML

**Backend & Infrastructure**
- Supabase (BaaS)
- PostgreSQL
- SQLite

**Architecture & Patterns**
- MVVM
- Dependency Injection
- Repository Pattern
- Layered Architecture

**Target Platforms**
- Android
- iOS
- macOS (MacCatalyst)
- Windows
