---
title: Configuring the application
date: 2018-01-09
---

1. Open the project directory in finder. You can do this with the following command
   ```bash
   open .
   ```
1. Then double click the `Core ML Vision.xcodeproj` file to open the project in Xcode
![](assets/9_0_open_project.png)
1. In Watson Studio, make your way back to your project's **Assets** tab.
![](assets/arduino_data_assets_list.png)
1. Then open your model and copy your **ModelID**. Keep it handy for later.
![](assets/arduino_model_id.png)
1. Open the associated visual recognition service.
![](assets/arduino_associated_service.png)
1. Navigate to the **Credentials** tab.
![](assets/arduino_credentials.png)
1. Copy your **"apikey"** and keep it handy for later.
![](assets/arduino_api_key.png)
1. Open the file called `CameraViewController.swift` and add your ModelIDs. They should be added as follows:
  ```
  static let modelIds = ["Arduino_Part_Id_461417312","Arduino_Fault_1907642704"]
  ```
![](assets/9_6_add_model_id.png)
1. Then open the file called `Credentials.plist` and add your api key.
![](assets/9_7_add_api_key.png)