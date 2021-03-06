# Report

## Attribute Inference Attack

| Dataset | Target Acc. | Attribute | Attack Performance (Accuracy) | Guessing Baseline
|---      |---          |---        |---                            |---
| AT&T    | ~0.87       | Glasses   | ~0.75                         | 0.5
| UTKFace | ~0.80       | Race      | ~0.53                         | 0.2

--- 

## Membership Inference Attack

| Dataset | Target Acc. | Attack Performance (Accuracy)
|---      |---          |---
| AT&T    | ~0.87       | ~0.53
| CIFAR10 | ~0.56       | ~0.53
| MNIST   | ~0.99       | ~0.56
| UTKFace | ~0.80       | ~0.75

---

## Model Inversion Attack

We were able to create adversarial samples. 
The target model predicts the correct label with a probability up to 1, but unfortunately the adversarial image does not look like the original one.