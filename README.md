#  Medical image classification with [fast.ai](https://www.fast.ai) on [Render](https://render.com)

This repo is based in [fast.ai](https://github.com/fastai/fastai) model for Render.

The Deep Learning module has been trained with the HAM10000 2018 ISIC dermoscopic images,
achieving 92,3% accuracy.

This application can be found in: https://skin.onrender.com. You can test it with your own images!
It has been modified to support heroku.

You can test locally installing Docker and using the command:

```
docker build -t skin . && docker run --rm -it -p 5000:5000 skin
```

You can find the Render deployment guide in https://course.fast.ai/deployment_render.html.

Please use [Render thread inside fast.ai forum](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
