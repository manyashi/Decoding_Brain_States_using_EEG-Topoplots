# Decoding_Brain_States_using_EEG-Topoplots

This project focuses on using machine learning to decode brain activity from EEG (Electroencephalography) data. By analyzing EEG topoplots—visual maps of brain activity—we aim to classify different brain states, which can have exciting applications in healthcare and technology.

About-
EEG Basics: EEG measures brain activity using electrodes on the scalp. It captures the brain’s electrical signals, which can be visualized as "topoplots" showing activity patterns.

Why This Matters-
Healthcare: Helps diagnose neurological conditions like epilepsy or Alzheimer’s.
Tech Innovations: Supports brain-computer interfaces (BCIs), which let people control devices with their thoughts.

Our Goal-
We’re building machine learning models to classify EEG topoplots into specific brain states. For example, identifying if someone is resting, imagining movement, or performing a task.

The Data-
Intel Image Dataset: Includes images like buildings and forests, used to test and train our models.
CIFAR-10 Dataset: Includes everyday objects like cars and airplanes, giving us diverse data to work with.

The Process-
Prepping the Images: Resized them to a standard size (64x64 pixels) and normalized the colors to make training easier.
Building the Models:
Model 1: Used 3 layers of filters to extract image features, plus some final layers for making predictions. Accuracy: ~84%.
Model 2: A simpler version with 2 layers. Accuracy: ~67%.
Training & Testing: We trained the models using thousands of images, checked their accuracy, and fine-tuned the process.

Conclusion-
Model 1 worked well for classifying the images.
Visual tools like confusion matrices and accuracy graphs helped us see where the models performed well (or struggled).
