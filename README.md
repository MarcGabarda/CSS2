### How to run this notebook (Google Colab)
1. Open the notebook in Google Colab.
2. Upload both dataset files into the session's **`/content`** folder (the default working directory):
   - In the left sidebar, click the **Files** icon (folder), then the **Upload** button, and select:
     - `pone_0206767_s002.xlsx` (Zendle et al., 2019 — player survey data)
     - `game_coding_50games.xlsx` (original game coding dataset)
   - **Note:** uploaded files are stored in session storage only and are deleted when the runtime disconnects, so they must be re-uploaded each session.
3. Install dependencies by running this in a cell:
   `!pip install pandas scipy matplotlib seaborn openpyxl`
4. Run all cells top to bottom (`Runtime → Restart and run all`).
