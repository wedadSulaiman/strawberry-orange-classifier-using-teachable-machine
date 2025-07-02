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
| `strawberry test2.jpg` | Sample image used for testing the model |
| `screenshot.png` | Screenshot showing model prediction result |

## How to Run(using google colab):
1. Open the `SrwaberryandOrange.ipynb` file in [Google Colab]([https://colab.research.google.com/](https://colab.research.google.com/drive/1wbFOtHXLJpopftxTA7N4d1LmOZxEpUa5?usp=sharing)). 
2. Upload the following files:
- `keras_model.h5`
- `labels.txt`
- A test image (e.g. `strawberry test2.jpg`)
3. Run all the code cells to load the model and make a prediction.
4. The predicted class and confidence score will appear as output.
  
## for example this image:
![strawberry test2](https://github.com/user-attachments/assets/f810640a-071a-482a-a41b-a4b1d5a85f1b)

## after teste in model:
![Screenshot 2025-07-02 050313](https://github.com/user-attachments/assets/ce286ae1-8296-4d1c-9433-96ba099406a9)


## output after test in google colab is :
![Screenshot 2025-07-02 064633](https://github.com/user-attachments/assets/3fd8f56a-08b0-4e19-a462-52459745a654)


