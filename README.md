# 📚 CMT Conference Finder

## Project Description
While applying to conferences, it was difficult to find all opportunities because information was scattered across the web.  
While using Microsoft CMT, I discovered the "All Conferences" section, which listed multiple conferences at once.  
To make this list usable:

- I copied the full conference list into a text file.
- Used **pandas** to process and filter:
  - Only future conference dates.
  - Only **International conferences** and conferences held **in India**.
- Generated two outputs:
  - An **Excel file** (`Conference_data.xlsx`) for easy sorting.
  - An **HTML file** (`Hyperlinked_conferences.html`) with clickable conference links for direct access.

This project helps streamline the conference application process by organizing relevant events in a structured way.

---

## Project Structure
```bash
conference-finder-cmt/
│
├── .ipynb_checkpoints/                  # Auto-saved notebook checkpoints (ignore)
│
├── .gitignore                            # Specifies files/folders to ignore
│
├── dataset.txt                           # Raw text data copied from Microsoft CMT
│
├── Filtered_International_Indian_2025_CMT_Conferences.ipynb  # Main notebook for filtering and hyperlinking
│
├── Conference_data.html                  # HTML export of all conference data
│
├── Conference_data.xlsx                  # Excel sheet with filtered conferences
│
├── Hyperlinked_conferences.html          # Final HTML with clickable conference links
│
├── README.md                             # Project documentation
│
└── requirements.txt                      # Python dependencies
```

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/conference-finder-cmt.git
   cd conference-finder-cmt
   ```

2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**:
   - Open `Filtered_International_Indian_2025_CMT_Conferences.ipynb`.
   - Follow the steps to clean, filter, and export the conference list.

4. **View the Outputs**:
   - Browse conferences through `Hyperlinked_conferences.html`.
   - Or open `Conference_data.xlsx` for spreadsheet view.

---

## Future Enhancements 🚀

- **Dynamic Fetching**:  
  Replace the manual copy-paste of conferences with an automated scraper or an API-based system.

- **Host on GitHub Pages**:  
  Deploy the final clickable conference list (`Hyperlinked_conferences.html`) through GitHub Pages for public access.

- **Advanced Filtering Options**:  
  Filter by field (AI, Systems, Networking, etc.), submission deadlines, or conference format (virtual, hybrid, in-person).

- **Mobile-Friendly View**:  
  Improve HTML styling to make the conference list easier to browse on mobile devices.

---

## How to Contribute

- Fork this repository.
- Create a new branch (`git checkout -b feature-branch-name`).
- Commit your changes.
- Push to your branch and open a Pull Request.

---

## License

This project is licensed under the [MIT License](LICENSE).

