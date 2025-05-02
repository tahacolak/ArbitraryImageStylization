README File<br>

📌 Features 🖼️ Transfer style from one image to another (e.g., from a painting to your selfie)

⚙️ Runs locally in any Python environment (VS Code, PyCharm, terminal, etc.)

🧠 Powered by TensorFlow Hub’s pre-trained arbitrary style transfer model

📷 Output is saved automatically and displayed with original images

🛠️ Requirements:

Install the required Python packages:

!pip install tensorflow_hub pip install tensorflow tensorflow_hub pillow matplotlib ✅ Make sure you are using Python 3.7+ ✅ Internet connection is required to download the model from TensorFlow Hub

🚀 How to Use Place your content image (e.g., content.jpg) and style image (e.g., pixar_style.jpg) in the project folder.

Run the script:

python style_transfer.py When prompted, enter the file paths for both images:

Input Image(example: content.jpg): content.jpg Style Image (example: pixar_style.jpg): pixar_style.jpg

The script will:

Load and preprocess the images Apply the style Save the result as stylized_output.jpg Display all images side-by-side

🧠 Behind the Scenes

This project uses this model from TensorFlow Hub: arbitrary-image-stylization-v1-256

It combines the content features of your image with the style features of the second image using a neural network.

📁 File Structure style_transfer.py # Main Python script content.jpg # Example content image (user-provided) pixar_style.jpg # Example style image (user-provided) stylized_output.jpg # Output image with style applied

📌 Example Use Cases

Turn your photo into a cartoon or Pixar-style portrait

Apply the texture of famous artworks like Van Gogh or Monet to your own photos

Generate creative visuals for design or social media content

📜 License This project is licensed under the MIT License.

🤝 Contributions Feel free to fork, suggest improvements, or create pull requests!
