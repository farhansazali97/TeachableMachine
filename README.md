# Teachable machine(Image project) using keras / tflite model
  + Client code(opencv) for teachable machine's Image project
  + Tested tensorflow lite(quant / unquant) and keras
  + Tested Raspberry OS / Ubuntu
  + https://teachablemachine.withgoogle.com/

# Execute
  + set Image project
  + Add a class
  + Training
  + Export Model (Tensorflow lite/Keras)
  + Run: python3 main.py --type [tflite|keras] --model [model_path] --labels [labels_path]
  
  python3 main.py --type tflite --model /home/jetson/Desktop/paan/tm/tflite_model/model_unquant.tflite --labels /home/jetson/Desktop/paan/tm/tflite_model/labels.txt
