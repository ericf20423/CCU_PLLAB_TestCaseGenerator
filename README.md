## Tcgen Plugin 使用說明


### 一、環境設置
Step1. 下載安裝eclipse，版本須為2018-09，安裝路徑不要包含中文。([點我下載](https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2018-09/R/eclipse-jee-2018-09-win32-x86_64.zip))

Step2. 下載安裝Xtext，從eclipse導覽列的 Help -> Install New Software... -> Work with的欄位貼上載點的網址
按下Enter後等待eclipse跑完，全選下載。([點我下載](https://download.eclipse.org/modeling/tmf/xtext/updates/composite/releases/))

Step3. 下載安裝Papyrus，從eclipse導覽列的 Help -> Install New Software... -> Work with的欄位貼上載點的網址
按下Enter後等待eclipse跑完，全選下載。([點我下載](https://download.eclipse.org/modeling/mdt/papyrus/updates/releases/2018-09/))

Step4. 下載安裝TcgenSetup.exe，安裝路徑選擇eclipse所在的資料夾。([點我下載](https://drive.google.com/open?id=1YQCuyN-neuGVMSnI0tkjJfIANZYZp-pr))


### 二、使用方法

1.  使用eclipsec.exe開啟eclipse後，在spec底下使用Papyrus進行類別圖以及狀態圖的描繪、
	並編寫程式的物件限制語言。
2.  完成後選擇導覽列的 Test -> Generate black box test case ，
	Tcgen Plugin 會自動產生限制邏輯圖、測試資料以及測試腳本。
3.  編寫程式通過測試腳本完成確保程式品質的TDD開發方式。


### About us

LAB307A

