## Tcgen Plugin Instructions


### I、Environment settings


  Step1.  Download and install eclipse, version is 2018-09. Do not include Chinese in the installation path.([Download Link](https://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/2018-09/R/eclipse-jee-2018-09-win32-x86_64.zip))

  
  Step2.  Download and install Xtext, From the eclipse navigation: Help -> Install New Software... -> Work with, Paste download URL.
Press Enter and wait for eclipse to finish downloading. Select all to download.([Download Link](https://download.eclipse.org/modeling/tmf/xtext/updates/composite/releases/))  

![](/img/HelpInstall3.png)

  Step3.  Download and install Papyrus，From the eclipse navigation: Help -> Install New Software... -> Work with, Paste download URL.
Press Enter and wait for eclipse to finish downloading. Select all to download.([Download Link](https://download.eclipse.org/modeling/mdt/papyrus/updates/releases/2018-09/))

  Step4.  Download and install TcgenSetup.exe, Select the folder where eclipse is installed.([Download Link](https://drive.google.com/open?id=1YQCuyN-neuGVMSnI0tkjJfIANZYZp-pr))


### II、How to use Tcgen Plugin

<ol start = "1">  
  <li>
  <font color="#dd0000">After using eclipsec.exe to open eclipse</font>, From the eclipse navigation: File -> New -> Other... -> CCU_Pllab -> Tcgen project. </br>
  <img src = "/CCU_PLLAB_TestCaseGenerator/img/tcgen.png" alt>
  </li>
</ol>  

  ![](/img/tcgen.png)
  
<ol start = "2">  
  <li>
  Create Papyrus project under the spec folder to draw class diagrams and state diagrams, and programming the objects constraint languages.
  </li>
</ol>

<ol start = "3">  
  <li>
  After specification was finished, From the eclipse navigation: Test -> Generate black box test case, Tcgen Plugin will automatically generate the constraint logic graph, test data and test scripts.
  </li>
</ol>

<ol start = "4">  
  <li>
  Write programs through test scripts,complete TDD(Test-Driven Development) method to ensure program quality.
  </li>
</ol>

### III、Quick Start

<ol start = "1">  
  <li>
  After creating a new tcgen project, you will find that we have prepared a sample specification in the spec folder.
This is a specification document describing the BoundedQueue class, which contains the class diagram and the object constraint language included in the papyrus project.
  </li>
</ol>  

![](/img/spec.png)

<ol start = "2">  
  <li>
  Double-click the BoundedQueue project and open the View of the class diagram, or open any related specification file. Such as BoundedQueue.ocl or BoundedQueue.uml. Then press the test button installed by the tcgen plugin in the eclipse navigation bar, select the "Method level black box test case" option.  
  </li>
</ol>

![](/img/testoption.png)

<ol start = "3">  
  <li>
  Wait for the execution of the plug-in to be completed, refresh the pllab project and you will find the constraint logic graph of BoundedQueue automatically generated in the clg folder, test cases and test scripts will also be automatically generated in the corresponding folder.
  </li>
</ol>

![](/img/generate.png)

### About us

CCU_LAB307A

