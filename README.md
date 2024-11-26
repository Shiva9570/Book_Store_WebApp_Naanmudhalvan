

# 🌟 **Book Store Web App - Naanmudhalvan** 🌟

Welcome to the **Book Store Web App Repository**, your go-to place for managing book collections and exploring the preview of our application!

---

## 🚀 **How to Get Started**

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



---

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

### Key Improvements:
1. **Clickable Hyperlinks:**
   - Your **email** is now clickable, and it will open the default email client.
   - Your **Instagram username** is linked directly to your Instagram profile.

2. **Logos:**
   - The **email logo** links to your email address.
   - The **Instagram logo** links to your Instagram page.

3. **Styling:**  
   Icons improve the visual appeal and usability of the contact section.

---

This README.md file is fully functional and styled for GitHub. Let me know if you need further changes!

