# Systematic Analysis of Underwater Image Enhancement and Object Detection

Underwater environments pose significant challenges to imaging systems due to factors like light attenuation and suspended particles, leading to poor visibility. Addressing these challenges is crucial for various applications such as marine research and underwater surveillance. Generative Adversarial Networks (GANs) offer a promising solution for enhancing underwater imagery by effectively dehazing images and improving object detection accuracy.

In addition to evaluating the performance of Generative Adversarial Networks (GANs) for image dehazing, this study extends its analysis to underwater object detection, particularly on marine animals. Detecting and tracking marine animals in underwater environments are critical for various applications, including ecological monitoring, biodiversity assessment, and marine conservation efforts. However, the challenges posed by poor visibility and environmental conditions make this task inherently complex. Due to noise, distortion, and occlusions, traditional object detection methods often struggle to accurately identify and localize marine animals in underwater imagery.

## DATASET 

The dataset has been taken from 'An Underwater Image Enhancement Benchmark Dataset and Beyond.' 
The paper can be viewed here: [[arXiv]](https://arxiv.org/pdf/1901.05495.pdf). 

Raw images : [Google Drive Link](https://drive.google.com/file/d/12W_kkblc2Vryb9zHQ6BfGQ_NKUfXYk13/view)  
Reference images: [Google Drive Link](https://drive.google.com/file/d/1cA-8CzajnVEL4feBRKdBxjEe6hwql6Z7/view)  
Testing/Challenge images: [Google Drive Link](https://drive.google.com/file/d/1Ew_r83nXzVk0hlkfuomWqsAIxuq6kaN4/view)   

For more details visit: https://li-chongyi.github.io/proj_benchmark.html

## RESULTS

### IMAGE DEHAZING

![Untitled Diagram drawio (1)](https://github.com/Anushkaghei/Underwater-Image-dehazing/assets/79694271/3d2f0560-ad84-4c3b-81f1-ec9eb7359684)


![gan drawio](https://github.com/Anushkaghei/Underwater-Image-dehazing/assets/79694271/125972aa-285e-48e0-b9a8-828df29a3f4d)

### OBJECT DETECTION

![Untitled Diagram drawio (2)](https://github.com/Anushkaghei/Underwater-Image-dehazing/assets/79694271/fc334729-b3ec-4ab2-906b-b79a4cfa00c1)


## STEPS TO RUN:

### PIX2PIX MODEL

```
Mention code snippets if any for execution here
```

### UWGAN MODEL

```
Mention code snippets if any for execution here
```

### CYCLEGAN MODEL

1. Open the CycleGAN ipynb file in Google Colab.
2. Change the runtime type to 'Python 3' and the hardware accelerator to 'T4 GPU'.
3. Execute each code cell sequentially.
4. Ensure that you grant permission to access your Google Drive account. This step is necessary for loading the dataset.

### U-SHAPED TRANSFORMER MODEL

```
Mention code snippets if any for execution here
```

### Evaluation metrics

1. Open the evaluation_metrics ipynb file in Google Colab.
2. Connect to a hosted runtime
3. Change the file paths for your raw, generated and reference images.
4. Execute each code cell sequentially.
