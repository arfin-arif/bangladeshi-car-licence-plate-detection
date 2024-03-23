# Bangladeshi Car License Plate Detection

## Project Description

The Bangladeshi Car License Plate Detection project aims to develop a robust license plate detection system tailored specifically for vehicles in Bangladesh. The project utilizes the YOLO (You Only Look Once) model from Ultralytics and a custom dataset containing images of various vehicles, including cars, buses, bikes, and trucks, each featuring license plates.

## How to Install and Run the Project

To install and run the project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/arfin-arif/bangladeshi-car-licence-plate-detection.git
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Download Pre-Trained YOLO Weights:**

   Download the pre-trained YOLO weights from Ultralytics and save them to the `models` directory.

   ```bash
   wget https://ultralytics.com/assets/yolov5/yolov5s.pt -O models/yolov5s.pt
   ```

4. **Run License Plate Detection:**

   Navigate to the project directory and run the detection script.

   ```bash
   cd bangladeshi-car-license-plate-detection
   !python /content/bangladeshi-car-licence-plate-detection/ultralytics/yolo/v8/detect/predict.py model='/runs/detect/train/weights/best.pt' source='/test.mp4'

   ```

5. **Training the Model:**

   If you want to train the model on your own dataset, refer to the Ultralytics YOLOv5 repository and follow the instructions.

6. **Evaluate Model Performance:**

Here is the result of the evaluation on the test set.
![result](https://github.com/arfin-arif/bangladeshi-car-licence-plate-detection/blob/main/runs/detect/train/results.png?raw=true)

7. **References:**

- [Ultralytics YOLOv5 Repository](https://github.com/ultralytics/yolov5)
- [Roboflow Dataset](https://universe.roboflow.com/kaiser-durden/bangladeshi-license-plate-fonfq/dataset/1)

Feel free to reach out if you have any questions or need further assistance!
