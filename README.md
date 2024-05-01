# uta-vision

Group project for computer vision focusing on adversarial attacks against image identifiers

## Members

- Landon Moon

- Parker Steach

- Justin Fellows

- Gilbert Lavin

## Code

The code of this project followed a tutorial from https://pyimagesearch.com/2020/10/19/adversarial-images-and-attacks-with-keras-and-tensorflow/. The tutorial was followed initially to get a first working version, then some changes were made to test the bound of attacks on CNNs.

## Terminal Commands

- Classify an image normally:

    python .\predict_normal.py -i img/good/hog.jpg

- Generate, save, and classify an adversarial image:

    python .\generate_basic_adversary.py -i img/good/hog.jpg -o img/bad/hog.jpg -c 341
