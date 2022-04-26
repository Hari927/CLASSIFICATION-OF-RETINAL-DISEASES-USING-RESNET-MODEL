# CLASSIFICATION-OF-RETINAL-DISEASES-USING-RESNET-MODEL

** Introduction**
Diabetic retinopathy (DR) is a common diabetes complication that occurs when the retina’s blood vessels are damaged due to high blood sugar levels, resulting in swelling and leaking of the vessels. In an advanced DR stage, the vision may be lost completely. The percentage of blindness worldwide resulting from DR is 2.6%. Therefore, diabetes patients need regular screening of the retina to detect DR early, manage its progression and avoid the risk of blindness.

Diabetic Retinopathy is a disease with an increasing prevalence and the main cause of blindness among working-age population. The risk of severe vision loss can be significantly reduced by timely diagnosis and treatment. Systematic screening for DR has been identified as a cost-effective way to save health services resources. Automatic retinal image analysis is emerging as an important screening tool for early DR detection, which can reduce the workload associated to manual grading as well as save diagnosis costs and time. Many research efforts in the last years have been devoted to developing automated tools to help in the detection and evaluation of DR lesions. We are interested in automating this prediction using deep learning models. So we want to develop a computer aided diagnosis tool to detect the presence of diabetic retinopathy and classify whether it is a normal DR or an abnormal DR based on the features extracted.


The leaking blood and fluids appear as spots, called lesions, in the fundus retina image. Lesions can be recognised as either red lesions or bright lesions. Red lesions involve microaneurysms (MA) and haemorrhage (HM), while bright lesions involve soft and hard exudates (EX) as shown in Figure 1. The small dark red dots are called MA and the larger spots are called HM. Hard EX appears as bright yellow spots, while soft EX, also called cotton wool, appears as yellowish-white and fluffy spots caused by nerve fibre damage. The five DR stages depend on the types and numbers of lesions on the retina image, as shown in Table 1. Samples of the various DR stages (no DR, mild DR, moderate DR and proliferative DR) are shown in Figure 2.

![image](https://user-images.githubusercontent.com/79081714/165319683-d9b895ab-70dc-48b3-a6b2-443363296f4b.png)
 Figure-1: Different types of DR lesions

![image](https://user-images.githubusercontent.com/79081714/165319787-2025ff19-ff7b-40fc-b54e-9b8d4ed5bd86.png)
 a). No DR
 
![image](https://user-images.githubusercontent.com/79081714/165319854-d2c8658d-7bf3-442b-85c2-8039e1325efa.png)
 b). Mild
 
![image](https://user-images.githubusercontent.com/79081714/165320014-8ff0f908-651e-4284-9e92-0d634bc0681c.png)
c). Moderate

![image](https://user-images.githubusercontent.com/79081714/165320098-81db89fe-2c8d-412e-aa13-428a4b31f8f1.png)
 d). Proliferative DR

**Figure-1.2: Different stages of DR**


Table-1: The DR stages depending on lesions classification

DR Severity               -Level	Lesions
0-No DR	                    No lesions.
1-Mild DR	                  MA only.
2-Moderate DR	              More than just MA but less than severe DR.
3-Severe DR	                More than 20 intraretinal HM in each of 4 quadrants;
                            Definite venous beading in 2+ quadrants; Prominent intraretinal                                 microvascular abnormalities in 1+ quadrant and no signs of                                       proliferative DR.
4-Proliferative DR	        Neovascularization, pre-retinal HM.


The manual diagnosis of DR by ophthalmologists is time-consuming, requires considerable effort, and is prone to disease misdiagnosis. Therefore, using a computer-aided diagnosis system can avoid misdiagnosis and reduce overall cost, time and effort. During the last decade, deep learning (DL) approach has emerged and been adopted in many fields, including medical image analysis. DL can identify features accurately from input data for classification or segmentation and typically outperforms all traditional image Sensors 2021, 21, 3704 3 of 22 analysis techniques.
Recent advancements in Artificial Intelligence (AI) and the increase of computational resources and capabilities have created the opportunity to develop Deep Learning (DL) applications for accurate DR detection and classification.

**Process Flow Diagram**
![image](https://user-images.githubusercontent.com/79081714/165320818-c81a1862-f824-40a6-908f-805f43a9acdf.png)

**Architecture**
RESNET includes the skip connection feature which enables the training of 152 layers without vanishing gradient issues. The architecture of the RESNET model is given below:

![image](https://user-images.githubusercontent.com/79081714/165321102-0a13a0b0-55b2-490b-a40e-9ad763d28f43.png


**Output-**
![image](https://user-images.githubusercontent.com/79081714/165318254-f3172e79-fb44-4909-b1ad-9833f2b15607.png)
![image](https://user-images.githubusercontent.com/79081714/165318350-3ece040a-1cd0-4a74-9324-67f6f0d2059e.png)
![image](https://user-images.githubusercontent.com/79081714/165319226-8b705aa7-de16-441e-800e-136d01c6c869.png)
**Conclusion and Future Work**
In this project we are able to classify the input retinal images into different stages of DR using the pre-trend RESNET model. The GUI we develop will be helpful for both doctors and also the common people.
Our future work is to convert the GUI into a mobile application. We are also trying to improve the accuracy.
