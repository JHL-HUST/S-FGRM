## REQUIREMENTS

- Python 3.6.5
- Tensorflow 1.12.0 
- Numpy 1.15.4 
- cv2 3.4.2
- scipy 1.1.0

## EXPERIMENTS

The code consists of five Python scripts. You should download the [data](https://drive.google.com/open?id=1CfobY6i8BfqfWPHL31FKFDipNjqWwAhS) and [pretrained models](https://drive.google.com/open?id=10cFNVEhLpCatwECA6SPB-2g0q5zZyfaw) before running the code. Then place the data and pretrained models in [dev_data/](dev_data) and [models/](models), respectively.

### Example usage

After cloning the repository you can run the giving attack code to generate adversarial examples and then evaluate the attack success rate.

- Generate adversarial examples:

```
python smi_fgrm.py
```

- Evaluate the attack success rate：

```
python simple_eval.py
```

## Acknowledgments

Code refer to: [SI-NI-FGSM](https://github.com/JHL-HUST/SI-NI-FGSM)


