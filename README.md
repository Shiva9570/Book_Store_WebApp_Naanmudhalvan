

# 🌟 **Book Store Web App - Naanmudhalvan** 🌟

Welcome to the **Book Store Web App Repository**, your go-to place for managing book collections and exploring the preview of our application!  

---

## 📹 **Video Preview**
Click below to directly play the video preview of the app!  
[![Video Preview](https://img.icons8.com/color/96/000000/play.png)](https://drive.google.com/file/d/1lVILTZxAW9KFQbsTs9qziVxPN7u5AyDU/view?usp=sharing)

---

## 📂 **Repository Contents**
- **`books/`**: Contains all book PDFs.
- **`scripts/`**: Scripts to automate book management tasks.
- **`previews/`**: Contains preview videos and images.

---

## 🚀 **How to Initiate the Project**

### Step 1: Clone the Repository
```bash
git clone https://github.com/Shiva9570/Book_Store_WebApp_Naanmudhalvan.git
cd Book_Store_WebApp_Naanmudhalvan

Step 2: Set Up the Project

Run the setup script to initialize the project structure:

./scripts/setup.sh

Step 3: Add a New Book

To add a book to the books/ folder, use the following command:

./scripts/add_book.sh "path-to-book.pdf"

Step 4: View the Video Preview

You can directly view the app demo by clicking on the video preview link.


---

📧 Contact Information


For any queries or additional information:

Email:

shivendra9570.mishra@gmail.com

Instagram:

@vierdo.musicx


🤝 Contributing

We welcome contributions! Feel free to fork the repository, create a new branch, and submit a pull request.


---

🛠 Scripts

1. setup.sh: Initializes the repository structure.

#!/bin/bash
# Script to set up the repository structure

mkdir -p books previews scripts
touch .gitignore README.md
echo "Setup completed. Repository is ready for use."

2. add_book.sh: Adds a new book to the repository.

#!/bin/bash
# Script to add a new book

if [ "$#" -ne 1 ]; then
  echo "Usage: $0 <path-to-book>"
  exit 1
fi

cp "$1" books/
echo "Book $(basename "$1") added to the repository."


---

🌟 Thank You for Visiting! 🌟

Feel free to explore, contribute, or reach out with any questions!

---

### Explanation of Changes
1. **Image Embedding Code:**
   - **Email:** Added `<img>` with a link using `https://img.icons8.com/color/48/000000/email.png`.
   - **Instagram:** Used `<img>` with a link pointing to `https://img.icons8.com/color/48/000000/instagram-new.png`.

2. **Clickable Links:**  
   Icons now link directly to the email client or Instagram profile.

### How It Works
- GitHub allows embedding remote images in README files using HTML `<img>` tags.
- Icons are sourced from [Icons8](https://icons8.com/), a reliable source for free icons.

You can now copy-paste this code, and the logos will appear in your README file. Let me know if you need further assistance!

