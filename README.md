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

<ol>  
  1.  **After using eclipsec.exe to open eclipse**, From the eclipse navigation: File -> New -> Other... -> CCU_Pllab -> Tcgen project.   

  ![](/img/tcgen.png)

  2.  Create Papyrus project under the spec folder to draw class diagrams and state diagrams, and programming the objects constraint languages.

  3.  After specification was finished, From the eclipse navigation: Test -> Generate black box test case, Tcgen Plugin will automatically generate the constraint logic graph, test data and test scripts.

  4.  Write programs through test scripts,complete TDD(Test-Driven Development) method to ensure program quality.
</ol>

### III、Quick Start

1.  After creating a new tcgen project, you will find that we have prepared a sample specification in the spec folder.
This is a specification document describing the BoundedQueue class, which contains the class diagram and the object constraint language included in the papyrus project.

![](/img/spec.png)

2.  Double-click the BoundedQueue project and open the View of the class diagram, or open any related specification file. Such as BoundedQueue.ocl or BoundedQueue.uml. Then press the test button installed by the tcgen plugin in the eclipse navigation bar, select the "Method level black box test case" option.  

![](/img/testoption.png)

3.  
### About us

CCU_LAB307A

