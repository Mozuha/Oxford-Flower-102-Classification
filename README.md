# Oxford-Flower-102-Classification

![Oxflower-Classification-Demo](https://user-images.githubusercontent.com/42855551/86756734-92873180-c07d-11ea-9325-497d8df23318.gif)

## Description
Classify an flower image with fine-tuned ResNet50 model based on [102 Category Flower Dataset](http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html)

## Command
```zsh
python3 -m venv --system-site-packages ./venv
. venv/bin/activate
cd venv
pip install -r ../../../requirements.txt
cd ../../Frontend
yarn start-api  // run flask server
```
Then go to http://localhost:5000/
