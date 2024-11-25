# BKAI-IGH-NeoPolyp_Asignment_3_Intro_to_Deep_Learning

## Requirements

To install the necessary packages, please run the following command in your terminal:
    ```
    pip install albumentations==1.0.3 segmentation-models-pytorch==0.3.0 torchinfo wandb torchsummary torchgeometry pyyaml optuna optuna-integration[pytorch_lightning]`
    ```

## Instructions to Run Inference

1. Clone the repository:
    ```
    git clone https://github.com/xt2201/BKAI-IGH-NeoPolyp_Asignment_3_Intro_to_Deep_Learning.git
    cd 'BKAI-IGH-NeoPolyp_Asignment_3_Intro_to_Deep_Learning'
    ```

2. Ensure the model checkpoint is in the `checkpoints/` directory:
    - Download the checkpoint from the provided [link](https://drive.google.com/file/d/1WIYaL4M0VQyl_qUcUrsuSu5QzgQcYo6G/view?usp=sharing).
    - Place the `best_model.pth.tar` file in the `checkpoints/` directory of this repository.

3. Run the inference script:
    ```
    python3 infer.py --image_path image.jpeg
    ```

4. The segmented image will be saved in the current working directory with the prefix segmented_. For example, segmented_image.jpeg.
