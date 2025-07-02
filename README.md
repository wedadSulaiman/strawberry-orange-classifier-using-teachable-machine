# strawberry-orange-classifier-using-teachable-machine
this project uses a machine learing model trained with Teachable Machine by Google(https://teachablemachine.withgoogle.com/train/image) to classify images of **strawberries** and **oranges**.
The model was trained on:
- 10 images of strawberries
- 10 images of oranges

## project files:
| File | Description |
|------|-------------|
| `keras_model.h5` | Trained model exported from Teachable Machine |
| `labels.txt` | Class labels used in the model (Strawberry, Orange) |
| `SrwaberryandOrange.ipynb` | Google Colab notebook used to run predictions |
| `strawberry test.jpg` | Sample image used for testing the model |
| `screenshot.png` | Screenshot showing model prediction result |


## How to run the model in Teachable Machine:
1. ** open google drive file (

## How to Run(using google colab):
1. Open the `SrwaberryandOrange.ipynb` file in [Google Colab]([https://colab.research.google.com/](https://colab.research.google.com/drive/1wbFOtHXLJpopftxTA7N4d1LmOZxEpUa5?usp=sharing)). 
2. Upload the following files:
- `keras_model.h5`
- `labels.txt`
- A test image (e.g. `strawberry test.jpg`)
3. Run all the code cells to load the model and make a prediction.
4. The predicted class and confidence score will appear as output.
  
## for example this image:
![strawberry test](https://github.com/user-attachments/assets/05513c15-8591-4ce9-81ef-b4751ba51c86)


## after teste in model:
![Screenshot 2025-07-02 135113](https://github.com/user-attachments/assets/cf9eddc9-4019-4e03-972b-3047d7ad2d8b)



## output after test in google colab is :
![Screenshot 2025-07-02 140355](https://github.com/user-attachments/assets/edca5077-e37d-4fd5-a25d-3067821012db)


the model in googke drive:
https://drive.google.com/file/d/1b8ZRdinvGv87VKXtityndQ9IUruq_VBw/view?usp=drive_link

