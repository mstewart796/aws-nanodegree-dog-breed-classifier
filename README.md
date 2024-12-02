Here's a polished and improved version of your README file with better formatting, consistent style, and enhancements for readability and professionalism:

---

# **Image Classification for a City Dog Show**

This project is part of my **AWS AI Nanodegree Program**. It is a command-line image classifier that can:

1. Distinguish between dogs and non-dogs.
2. Identify specific dog breeds.

The program uses several Python scripts located in the **`data`** folder.

---

## **Features**

- **Dog vs. Non-Dog Classification:** Distinguishes if the image is of a dog or not.
- **Dog Breed Classification:** Identifies specific dog breeds for images classified as dogs.
- **Results Output:** Saves analysis and results to files for review.
- **Model Comparisons:** Tests three pretrained models: **AlexNet**, **ResNet**, and **VGG**.

---

## **How to Use**

1. Place the images you want to classify in the **`data/uploaded_images`** folder.  
   _(You may delete my personal sample images contained in the folder.)_

2. Run one of the following commands to classify the images.  
   _(Ensure your terminal is in the **`data`** folder before executing the commands.)_

   - **For ResNet:**
     ```bash
     python check_images.py --dir uploaded_images/ --arch resnet --dogfile dognames.txt > resnet_uploaded-images.txt
     ```
   - **For AlexNet:**
     ```bash
     python check_images.py --dir uploaded_images/ --arch alexnet --dogfile dognames.txt > alexnet_uploaded-images.txt
     ```
   - **For VGG:**
     ```bash
     python check_images.py --dir uploaded_images/ --arch vgg --dogfile dognames.txt > vgg_uploaded-images.txt
     ```

3. **Results Output:**  
   The results will be saved in one of the following files depending on the model used:

   - **`data/alexnet_pet-images.txt`**
   - **`data/resnet_pet-images.txt`**
   - **`data/vgg_pet-images.txt`**

   **Tip:** You may want to delete the content of these files before running the program, as they currently contain sample results.

4. **Optional:**  
   Use the `run_model_batch.bat` file to test all three models simultaneously on a Windows machine or the `run_model_batch.sh` file if you are running a Linux based OS.

---

## **Notes**

- Ensure Python is installed and set up correctly in your environment.  
- This project requires some libraries like `torch` and `PIL`. Refer to the **Udacity Nanodegree documentation** for the required dependencies.

---

## **References**

- **[Udacity](https://www.udacity.com/)**
- **[AWS AI Programming with Python Nanodegree](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089)**

---

This improved version includes proper Markdown elements like **bold text**, consistent formatting, and a more professional tone. It ensures readability and aligns with best practices for creating clear and engaging documentation.
