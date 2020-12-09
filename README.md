# Cognitive Services Quickstart

[Azure Cognitive Services Quickstart](https://docs.microsoft.com/azure/cognitive-services/?WT.mc_id=spatial-0000-ayyonet) completed steps divided into branches.

## Custom Vision

[Azure Cognitive Services - Custom Vision Quickstart](https://docs.microsoft.com/azure/cognitive-services/custom-vision-service/?WT.mc_id=spatial-0000-ayyonet) completed steps divided into branches.

### [Object Detection - Node.js SDK](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=spatial-0000-ayyonet)

## Running locally

1. Create a `.env` file and add your variables that are defined in '.env.example' file, then run the following commands:

2. Install dependencies

```bash
npm install
```

3. Start the sample file

```bash
node sample.js
```

Or by running

```bash
npm st
```

 ####  [Step-1 branch](https://github.com/Yonet/CognitiveServicesQuickstart/tree/step-1)

 - Create a new folder for your project, ex: CognitiveServices.
 - [Initialize a git project.](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)

 ```bash
 git init
 ```

 - Initialize an [npm project.](https://docs.npmjs.com/creating-a-package-json-file)

 ```bash
 npm init
 ```

 - Install the [Custom Vision SDK](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=spatial-0000-ayyonet#install-the-custom-vision-sdk)

 ```bash
npm install @azure/cognitiveservices-customvision-training
npm install @azure/cognitiveservices-customvision-prediction
 ```

- Get the [Training and prediction Keys](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=spatial-0000-ayyonet#get-the-training-and-prediction-keys)

- Add the Keys as environment variable on your console.

```bash
export trainingKey={your training key}
export predictionKey={your predictionKey key}
export predictionResourceId={your predictionResourceId key}
```

 - Create and add [sample.js file](https://docs.microsoft.com/azure/cognitive-services/Custom-Vision-Service/node-tutorial-object-detection?WT.mc_id=spatial-0000-ayyonet#CognitiveServicesQuickstart-github-ayyonet)

 - Change the [Key variables](https://github.com/Yonet/CognitiveServicesQuickstart/blob/d5d9fab5e40791e0752f4ecad8ec5a753d67d7b8/sample.js#L7) in your code to use your environment variables.

 ```js
const trainingKey = process.env.trainingKey;
const predictionKey = process.env.predictionKey;
const predictionResourceId = process.env.predictionResourceId;
 ```

