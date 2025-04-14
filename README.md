# KeyWordManager

**KeyWordManager** is a lightweight, browser-based application for managing keywords (tags) and their associated entries (like IDs, notes, chapters, diary entries, or file references). It's built entirely within a single HTML file using HTML, CSS, and vanilla JavaScript, requiring no installation or external dependencies beyond a modern web browser.

## What it Does

This tool provides a simple interface to:

*   **Create and Manage Tags:** Add new tags, edit existing tag names, and remove tags individually or in bulk.
*   **Associate Entries:** Link one or more text-based entries (e.g., document IDs, page numbers, filenames, short notes) to each tag.
*   **Visualize Relationships:** Clearly see which tags are associated with which entries and vice-versa. Hover tooltips provide quick previews of these associations.
*   **Search and Filter:**
    *   Quickly search for specific tags by name.
    *   Filter the tag list based on associated entries (either by typing or clicking an entry).
*   **Persist Data:**
    *   Load tag data from local `.json` files.
    *   Save the current tag set back to a `.json` file (using Save or Save As).
    *   Utilizes the browser's **File System Access API** for seamless file handling (requires user permission).
    *   Includes **LocalStorage backup** for unsaved changes per file if the API is unavailable, preventing data loss.
*   **User-Friendly Interface:**
    *   Clean, responsive design that adapts to different screen sizes.
    *   Light and Dark mode themes.
    *   Keyboard navigation support for accessibility and efficiency.
    *   Undo/Redo functionality for common actions.
    *   Clear visual feedback for selections, unsaved changes, and operations.
    *   Drag-and-drop support for loading `.json` files.

## How it's Helpful & Use Cases

KeyWordManager is useful in various scenarios where you need to organize information or assets using tags/keywords without relying on complex software:

*   **Personal Knowledge Management:** Tagging notes, ideas, research papers, or code snippets with relevant keywords for easy retrieval. *Example: Tagging journal entries with themes like "Dream Recall", "Meditation Technique", "OBE Phase".* (As per the original inspiration!)
*   **Digital Asset Organization:** Managing keywords for photos, videos, or design assets stored locally. The 'entries' could be filenames or unique IDs.
*   **Content Creation:** Keeping track of tags used for blog posts, videos, or social media content.
*   **Research:** Tagging data points, literature references, or interview snippets with codes or themes.
*   **Simple Project Management:** Using tags to categorize tasks or resources associated with different project identifiers.
*   **Offline Tagging:** Because it runs entirely in the browser, you can use it offline once the HTML file is loaded. Data is saved locally to your machine.

*In essence, it provides a straightforward, private, and offline-first way to create and manage many-to-many relationships between your keywords and the items they describe.*

## Getting Started

1.  Download the `KeyWordManager-V[version].html` file.
2.  Open the file in a modern web browser (like Chrome, Edge, Firefox, Safari).
3.  Start adding tags or open an existing `.json` file (using the File menu, placeholder buttons, or drag-and-drop).

> **Note:** Full file saving functionality relies on browser support for the **File System Access API**. Without it, saving uses LocalStorage backups, and you'll need to use "Save As..." if the API becomes available later or manually manage the JSON.

## License and Usage

KeyWordManager is provided free of charge.

The source code contained within the HTML file is intended for public use. You are free to use, study, modify, and distribute this software as you see fit. There are no restrictions on its use or modification for personal or commercial purposes.

The software is provided "as is", without warranty of any kind, express or implied.
