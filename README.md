# MemoryVault: Time Capsule Creator

## Overview 

The "MemoryVault" is an innovative Java-based desktop application designed to allow users to create, store, and revisit digital time capsules containing personal memories, goals, images, and notes, which are locked until a user-specified future date. Built using JavaFX for a rich graphical user interface (GUI), SQLite for data persistence, and incorporating basic encryption techniques, this project combines emotional storytelling with practical utility, making it a unique tool for personal reflection, motivation, and legacy preservation. The application is highly customizable, user-friendly, and offers a nostalgic yet modern experience, appealing to a wide range of users from individuals to families and even small teams.

## Tech stack

**Programming Language**: Java (JDK 17+)

**Framework**: JavaFX for GUI development, providing a cross-platform desktop experience.

**Database**: SQLite for lightweight, local data storage, with a table schema including id, title, memory, unlock_date, and image_path columns.

**Libraries**:
sqlite-jdbc for SQLite connectivity.

JavaFX controls and media libraries for UI and image handling.

**Encryption**: Base64 encoding for memory text (a basic security measure; advanced encryption like AES can be added).

**Dependencies**: Managed via manual JAR inclusion or Maven for easier setup.

## Use Case in Real Life
**Personal Memories Preservation**: Users can store life events (e.g., wedding photos, travel notes) and revisit them years later.

**Goal Setting & Motivation**: Track personal goals (e.g., fitness progress with "before" photos) and review achievements on a set date.

**Gifts for Loved Ones**: Create surprise capsules with messages and images for birthdays or anniversaries.

**Journaling with Insights**: Record dreams or thoughts and analyze mood patterns after a period.

**Business Milestones**: Teams can document project starts and review progress upon completion.

**Legacy for Future Generations**: Parents can leave stories and photos for their children to unlock decades later.

**Creative Projects**: Artists can save drafts and review them after a creative break.

**Event Planning**: Store event details (e.g., wedding plans) and check them close to the date.

## Run Command

--module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml

## Screenshot

![Capsule](https://github.com/user-attachments/assets/a005b62c-7eb8-4250-a1c4-fbe70c0f5efd)

## Conclusion

The "MemoryVault" is a blend of technology and emotion, offering a practical yet heartfelt way to preserve and revisit life’s moments. Its simple yet extensible design makes it an excellent project for learning JavaFX, database handling, and UI development, while its real-life applications make it a valuable tool for personal and professional use. With further enhancements, it could evolve into a widely used app for memory-keeping and goal tracking.

