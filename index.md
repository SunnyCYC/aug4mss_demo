
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo page of Mixing-Specific Augmentation for Music Source Separation</title>

</head>
<body>
    <h1>Demo page of Mixing-Specific Augmentation for Music Source Separation</h1>

</body>
</html>


This is the demo page for the paper titled “Mixing-Specific Data Augmentation Techniques for Improved Blind Violin/Piano Source Separation”. 
<[**paper**](https://arxiv.org/abs/2008.02480)><[**github**](https://github.com/SunnyCYC/aug4mss)><[**pretrained models (GoogleDrive)**](https://drive.google.com/drive/folders/1YyLww3G7-Amu_bs8s9Wl3NceUcQuq3Or)>

## Introduction

The main purpose of this work is to allow users to apply mixing-specific data augmentation techniques to facilitate the training of a neural network model for source separation, in particular with the Open-Unmix model architecture.

The following section demonstrates the 16 test songs remixed from MedleyDB (unseen during training), and the predicted stems by Spleeter and two of our proposed models trained under data-rich scenario (**Model A**: Random Mixing, **Model B**: Wet).

Note that both Model A and Model B outperform Spleeter since Spleeter was not pretrained on violin data. Model A achieves higher SDR for piano stems, and the augmented Model B performes better for violin stems.

## Demo audio

#### JoelHelander_ExcessiveResistancetoChange_p0_v0

#### Input Mixture 
<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v0\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### JoelHelander_ExcessiveResistancetoChange_p0_v1

#### Input Mixture 
<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\JoelHelander_ExcessiveResistancetoChange_p0_v1\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v0

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v0\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v1

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v1\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v2

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v2\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v3

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v3\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v4

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v4\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v5

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v5\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v6

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v6\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_AnEveningWithOliver_p0_v7

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_AnEveningWithOliver_p0_v7\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_ImpressionsOfSaturn_p0_v0

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v0\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_ImpressionsOfSaturn_p0_v1

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_ImpressionsOfSaturn_p0_v1\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_TheFlaxenField_p0_v0

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v0\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MatthewEntwistle_TheFlaxenField_p0_v1

#### Input Mixture 
<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MatthewEntwistle_TheFlaxenField_p0_v1\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### MutualBenefit_NotForNothing_p0_v0

#### Input Mixture 
<audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\MutualBenefit_NotForNothing_p0_v0\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

#### TheKitchenettes_Alive_p0_v0

#### Input Mixture 
<audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0.mp3" controls="" preload=""></audio>

|    Model    |  Spleeter  |   Model A   |   Model B   |
|---|---|---|---|
|Violin Est.| <audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0\Estimates\Spleeter\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0\Estimates\DR_ORI_n2000\violin.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0\Estimates\DR_Wet_n2000\violin.mp3" controls="" preload=""></audio>|
| Piano Est.| <audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0\Estimates\Spleeter\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0\Estimates\DR_ORI_n2000\piano.mp3" controls="" preload=""></audio>|<audio src="Demo_mp3_15sec\TheKitchenettes_Alive_p0_v0\Estimates\DR_Wet_n2000\piano.mp3" controls="" preload=""></audio>|

