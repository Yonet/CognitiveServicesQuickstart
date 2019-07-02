# Cognitive Services Quickstart

[Azure Cognitive Services Quickstart](https://docs.microsoft.com/azure/cognitive-services/custom-vision-service/?WT.mc_id=CognitiveServicesQuickstart-github-ayyonet) completed steps divided into branches.

## Custom Vision

### [Object Detection - Node.js SDK](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=CognitiveServicesQuickstart-github-ayyonet)

 ####  [Step-1 branch]()

 - Create a new folder for your project, ex: CognitiveServices.
 - [Initialize a git project.](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)

 ```bash
 git init
 ```

 - Initialize an [npm project.](https://docs.npmjs.com/creating-a-package-json-file)

 ```bash
 npm init
 ```

 - Install the [Custom Vision SDK](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=CognitiveServicesQuickstart-github-ayyonet#install-the-custom-vision-sdk)

 ```bash
npm install @azure/cognitiveservices-customvision-training
npm install @azure/cognitiveservices-customvision-prediction
 ```

- Get the Training and prediction Keys(https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=CognitiveServicesQuickstart-github-ayyonet#get-the-training-and-prediction-keys)

- Add the Keys as environment variable on your console.

```bash
export trainingKey={your training key}
export predictionKey={your predictionKey key}
export predictionResourceId={your predictionResourceId key}
```

 - Create and add [sample.js file](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=#add-the-code)

 - Change the Key variables in your code to use your environment variables.

 ```js
const trainingKey = process.env.trainingKey;
const predictionKey = process.env.predictionKey;
const predictionResourceId = process.env.predictionResourceId;
 ```

