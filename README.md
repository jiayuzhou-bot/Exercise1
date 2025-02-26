Exercise1 - Checkerboard Pattern Generator

📌 Project Overview

This project generates a checkerboard pattern using Python with numpy and matplotlib. The colormap used for visualization can be modified easily.

📂 Project Structure

Exercise1/
│── checkerboard.py  # Main script to generate checkerboard pattern
│── README.md        # Documentation

🔧 Prerequisites

Ensure you have Python 3.10+ installed. You can check your Python version with:

python --version

📥 Installation

1️⃣ Clone the repository

git clone https://github.com/jiayuzhou-bot/ex1-ZhouJiayu.git
cd ex1-ZhouJiayu

2️⃣ Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows

3️⃣ Install dependencies

pip install numpy matplotlib

▶️ Running the Project

To generate and visualize the checkerboard pattern, run:

python checkerboard.py

🎨 Changing the Colormap

The colormap used in plt.imshow() can be modified in checkerboard.py. Locate this line:

plt.imshow(checkerboard, cmap="viridis", interpolation="nearest")

Replace "viridis" with any other valid colormap, such as:

"gray"

"plasma"

"magma"

"inferno"

"jet"

🛠 Troubleshooting

If you encounter ModuleNotFoundError, ensure dependencies are installed:

pip install numpy matplotlib

If you face permission issues, try running Python as an administrator.

📜 License

This project is open-source and available under the MIT License.

✨ Contributing

Feel free to open an issue or submit a pull request if you have improvements!

📩 Contact

For any questions, reach out via GitHub Issues.

Happy coding! 🚀

