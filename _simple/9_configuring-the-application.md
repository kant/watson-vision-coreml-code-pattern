---
title: Configuring the application
date: 2018-01-09
---

1. Open the project directory in finder. You can do this with the following command
   ```bash
   open ..
   ```
1. Then double click the `QuickstartWorkspace.xcworkspace` file to open the project in Xcode

1. In Watson Studio, make your way back to your project's **Assets** tab.
![](assets/9_1_project_assets.png)
1. Then open each of your models and copy the **Model ID**. Keep this handy for later.
![](assets/9_2_model_id.png)
1. Open the associated visual recognition service.
![](assets/9_3_associated_service.png)
1. Navigate to the **Credentials** tab.
![](assets/9_4_credentials.png)
1. Copy your **"apikey"** and keep it handy for later.
![](assets/9_5_api_key.png)
1. Open the file called `ImageClassificationViewController.swift` and add your ModelID.
![](assets/step_9_add_model_id.png)
1. Next, in the same file, add your api key.
![](assets/step_9_add_api_key_single_model.png)
