This is a demo to depoly a bear classifier using Binder and volia

1. Train the model (Fastai Lesson 2) in the Google Colab instancea nd download the `export.pkl` 
1. Create your own GitHub repository in the Github homepage, such as this repo `fastai_model_deploy`
1. Open a terminal in your local machine, git clone your repo
1. Download `bear_classifier.ipynb`, `requirements.txt`
1. Add `export.pkl`, `bear_classifier.ipynb`, `requirements.txt` to your repo locally.
1. In your loacl terminal run the following commands to push these changes into your Github repo (or use VS Code)
    1. `git add .`
    1. `git commit -m “added files”`
    1. `git push -u origin main`
1. Open `https://mybinder.org/`, and refer the setup in `binder_setpu.png`
    1. Paste the URL of that repo into Binder's URL
    1. Change the File dropdown to instead select URL.
    1. In the "URL to open" field, enter /voila/render/name.ipynb (replacing name with the name of for your   notebook).
    1. Click the clickboard button at the bottom right to copyt the URL and paste it somewhere safe.
    1. Click Launch. then you should see the deploy app as in deploy_result.png if successed

